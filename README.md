# SSD_Light
Reference
---------
I refered `balancap's SSD` code. But his code is too heavy for me to understand. So I decided to write my own SSD code.<br>
My code is strongly similar to his.

Progress
--------
Under development
2019/3/5
Fixed a bug: Attempting to use uninitialized value<br>
Refactored loss_function, ssd_net and train_ssd

2019/3/5
Fixed a bug: with training loop goes on, the speed decreases.
Rewrite ground_truth_process.py. It was changed from using Tensorflow to using Numpy.

Next task:
Check loss_function.py
`nms` and `prediction`

Sadness
-------
Due to my fault. Old commit log was missiing.
