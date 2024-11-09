taint the node
```
kubectl taint nodes ip-192-168-18-93.ec2.internal hardware=gpu:NoSchedule
```

taint label the node
```
kubectl label nodes ip-192-168-18-93.ec2.internal hardware=gpu
```


