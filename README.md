# Pasos

Instalacion de argocd  
```
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.5.8/manifests/install.yaml
```

Instalacion de sealed secret   
![Instalando sealed](argo y sealed.png)
![Instalando sealed 2](kubeseal.png)

Creacion del sealed secret
![Sealed secret](image.png)

Creacion de la aplicacion en argocd  
![Argo](configurando repo.png)  
![Aplicar](aplicacion argocd.png)  
