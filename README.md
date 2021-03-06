# This repository was made for:
- bare metal kubernetes [v1.16]
- persistent volumes on [Ceph](https://docs.ceph.com/docs/master/rbd/rbd-kubernetes/) [v14.2.6]
- load balancer for nginx with [MetalLB](https://github.com/danderson/metallb) [v0.8.2]
- docker image from [netbox-community/netbox-docker](https://github.com/netbox-community/netbox-docker) [v2.7.2]

# Current versions:

```
- netbox 2.7.2
- postgres 11.4
- redis 5.0.6
- nginx 1.17.6
```

# Installation:

```
kubectl apply -f netbox-namespace.yaml
kubectl apply -f pvc-netbox.yaml 
kubectl apply -f redis-all.yaml
kubectl apply -f postgres-all.yaml
kubectl apply -f nginx-all.yaml
kubectl apply -f netbox-all.yaml
```

***
***
***

## Credits:

This is an original fork from: [vishnoisuresh/netbox-kubernetes](https://github.com/vishnoisuresh/netbox-kubernetes)
