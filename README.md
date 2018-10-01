# kubernetes_shared_volume_with_nfs

helm install stable/nfs-server-provisioner --name nfs-provisioner

kubectl create -f cm-claim.yaml

kubectl create -f fls-claim.yaml

kubectl create -f nginx-pod.yaml

kubectl create -f debian-pod.yaml
