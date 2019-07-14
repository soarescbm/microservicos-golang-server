

## Microserviços - Utilizando K8S

### 1 - Servidor Web - Nginx

  - k8s/nginx: 
    - deployment.yaml
    - configmap.yaml
    - service.yaml

### 2) Configuração do MySQL

  - k8s/mysql: 
    - deployment.yaml
    - persistent-volume.yaml
    - service.yaml      

### 3) Desafio Go!

  - src/app:
    - app.go
    - app_test.go
  - cloudbuild.yaml
  - Dockerfile
  - k8s/golang:
    - deployment.yaml
    - service.yaml      
  
  - Endereço do repositório:
  
```
https://cloud.docker.com/repository/docker/soarescbm/golang-server-otimizada
```


  - Nome da imagem: 

```
soarescbm/golang-server-otimizada   
```



  



