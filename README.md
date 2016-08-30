# Distributed-Mnist
> Distributed version of mnist tensorflow training

## Instructions
1. Simple Usage: 
 - for Parameter Server 0, ```python distributed_mnist.py --job_name='ps' --task_index=0```
 - for Parameter Server 1, ```python distributed_mnist.py --job_name='ps' --task_index=1```
 - so on ...
 - for Client 0          , ```python distributed-mnist.py --job_name='worker --task_index=0```
 - for Client 1          , ```python distributed-mnist.py --job_name='worker --task_index=1```
 - so on ...
2. 
