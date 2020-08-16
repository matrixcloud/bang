# Bang

炸了，国内各种镜像加速操作集合。

## Minikube

阿里云提供

```
curl -Lo minikube https://kubernetes.oss-cn-hangzhou.aliyuncs.com/minikube/releases/v1.12.1/minikube-darwin-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/
```

> [参考](https://developer.aliyun.com/article/221687)

## Helm charts

Azure CN

```
helm repo add stable http://mirror.azure.cn/kubernetes/charts/
```

> [参考](https://github.com/BurdenBear/kube-charts-mirror)

## Electron Prebuilt

```
export ELECTRON_MIRROR="https://npm.taobao.org/mirrors/electron/"
```
