Clone me, then (make sure ~/bin is in your path) ...
```
curl -o ~/bin/kubectl https://storage.googleapis.com/kubernetes-release/release/v1.3.4/bin/linux/amd64/kubectl
./etcd.sh
./apiserver
./kubelet.sh
./controller.sh
./scheduler.sh
./proxy.sh
```

kubectl should work without any configuration (localhost and insecure)
