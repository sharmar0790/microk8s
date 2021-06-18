# MICROK8S-KUBECTL

## Install microk8s on MAC OS

### Download

```
$ brew install ubuntu/microk8s/microk8s
```

### Install

```
$ microk8s install
```

### Check the status

```
$ microk8s status --wait-ready
```

### Enable the service you want

```
$ microk8s enable dashboard dns registry istio
```

### Check the all controllers

```
$ microk8s kubectl get all --all-namespaces
```

### See the dashboard

```
$ microk8s dashboard-proxy
```

### Start and stop

```
$ microk8s start # start the microk8s

$ microk8s start # stop the microk8s
```
