# Rolling updates

Provide a zero-downtime solution

## Available settings in the deployment
![](../images/05_rollingupdate1.png)
![](../images/05_rollingupdate2.png)
![](../images/05_rollingupdate3.png)

## Tricks

Save configuration in resource's annotations:
```
kubectl create -f file-deployment.yaml --save-config
```
![](../images/05_rollingupdate4.png)