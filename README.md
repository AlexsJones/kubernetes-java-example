# WIP: kubernetes-java-example
Complete java spring boot on k8s example


## Requirements
- As with most of my examples I peddle my simple helm replacement (for interpolating k8s files) called [vortex](https://github.com/AlexsJones/vortex)
- kubectl
- A connected kubernetes cluster

## Zero to Deployed...

```
./build_environment.sh default
kubectl create -f deployment/
```




## Istio

_I've included a commented out istio template for either connection from gateway or upstream service, you can tailor it to fit_

