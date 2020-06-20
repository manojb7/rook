# rook
kubectl create -f common.yaml
kubectl create -f operator.yaml
kubectl create -f cluster.yaml
find . -name storageclass.yaml
kubectl create -f ./csi/rbd/storageclass.yaml
