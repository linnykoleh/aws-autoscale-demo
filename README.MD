# Scale It!

## Create autoscale group that will contain one ondemand instance and will scale on spot instances.

### Launch ec2 instance

![1.png](images/1.png)

### Create AMI from the instance

![2.png](images/2.png)

### Create launch template

![3.png](images/3.png)

### Create autoscaling group

![4.png](images/4.png)

![5.png](images/5.png)

![6.png](images/6.png)

![7.png](images/7.png)

![8.png](images/8.png)

## Set up scaling policy based on AVG CPU usage.

![9.png](images/9.png)

## Set up scaling policy based on requests amount that allows non-linear growth.

![10.png](images/10.png)