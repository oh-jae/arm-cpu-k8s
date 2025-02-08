# arm-cpu-k8s
$ brew install minikube
$ curl -Lo minikube https://github.com/kubernetes/minikube/releases/download/v1.25.1/minikube-darwin-arm64 \
  && chmod +x minikube
$ sudo install minikube /usr/local/bin/minikube
$ minikube version
$ minikube start --driver=docker
# arm m1/m2/m3 cpu chip은 오직 docker 드라이버 사용이 강제
$ brew install kubectl
