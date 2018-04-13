# docker_registry_with_kubernetes_local_volume
Deploy a docker regitsry in kubernetes with local volume driver, The config is same from the offical charts repo [registry-chart](https://github.com/kubernetes/charts/tree/master/stable/docker-registry)

## require
 - kubernetes 1.9.3
 - docker registry 2.6.2
 - local volume enable
 - ingress enable

## steps
 1. first you should read https://blog.zhoulouzi.com/2018/03/kubernetes-local/ to enable local volume.
 2.  change the yaml in this repo. and apply them.



