# Selectors

Taint the node
```
kubectl taint nodes ip-192-168-28-182.ec2.internal hardware=gpu:NoSchedule

```
Label node

```
kubectl label nodes ip-192-168-28-182.ec2.internal hardware=gpu
```