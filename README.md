# apiserver-aggregation-sample
Kubernetes APIServer Aggregation Sample

## Create an apiserver sample

### Initialize the Project

```sh
apiserver-boot init repo --domain zoo.com
```

### Create an API resource

```sh
apiserver-boot create group version resource --group animal --version v1alpha1 --kind Cat --non-namespaced=false
```


## Reference

* https://github.com/kubernetes-sigs/apiserver-builder-alpha