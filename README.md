## RedisEnterprise
$ snap install helm --classic
$ git clone https://github.com/viveksrivastv/RedisEnterprise.git
$ cd RedisEnterprise
$ ls redis-cluster
$ helm install redis redis-cluster

$ kubectl get pods
NAME                                        READY   STATUS    RESTARTS   AGE
redis-enterprise-operator-c8cc6b76d-dqrts   2/2     Running   0          14m
