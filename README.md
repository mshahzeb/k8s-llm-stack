# k8s-llm-stack
Ready to run LLM stack configuration for Kuberenetes using Open Web UI / Ollama / HuggingFace TGI

```sh
kubectl create ns k8s-llm-stack
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.8.2/deploy/static/provider/cloud/deploy.yaml
kubectl apply -f nvidia-runtime.yaml -f ollama.yaml -f open-webui.yaml
```