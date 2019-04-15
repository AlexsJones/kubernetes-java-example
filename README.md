# WIP: kubernetes-java-example
Complete java spring boot on k8s example

I've pushed an image which is built from the WebApp folder to tibbar/webapp:v1 hopefully this gives you enough of a starting point on how to build k8s compatible apps and how to write manifests.

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

