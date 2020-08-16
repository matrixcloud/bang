# Bang

炸了，国内各种镜像加速操作集合。

## Homebrew

清华大学镜像

```
git -C "$(brew --repo)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git
git -C "$(brew --repo homebrew/core)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git
git -C "$(brew --repo homebrew/cask)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-cask.git
git -C "$(brew --repo homebrew/cask-fonts)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-cask-fonts.git
git -C "$(brew --repo homebrew/cask-drivers)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-cask-drivers.git
brew update
```

> [参考](https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/)

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
