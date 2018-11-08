### How to use

```
helm repo add kcd https://krisclarkdev.github.io/helm/
helm install kcd/wavefront-helm --name=wavefront --set wavefront_token=<<WAVEFRONT_TOKEN>> --set wavefront_url=<<WAVEFRONT_URL>> --set cluster_name=kubernetesclustername
```
