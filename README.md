# Kubernetes External Provisioner

This is an minamlistic External Provisioner skeleton.  The Provision(..) and Delete(...) calls throw errors and dont actually provision anything.  

# To Build
```make```

# To Run
``` ./_output/flex-provisioner --provisioner=csi-flex```


This can run outside of Kube with KUBECONFIG env variable set or specifying kubeconfig via CLI. Will also run as a container.





