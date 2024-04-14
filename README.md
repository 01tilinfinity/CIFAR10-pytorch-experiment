# experiment1
------------------------------
Base Model : Resnet18 
Dataset : CIFAR-10
Task : Image Classification(multilabel)
notation : Resnet 18 based model을 사용해 CIFAR-10 데이터셋에 대한 classificaiton task 성능을 **GPU Node 개수**에 따라 달리하는 실험입니다. [Horovod](https://github.com/horovod/horovod)를 사용하여 Data Parallelism을 구현하였습니다.
