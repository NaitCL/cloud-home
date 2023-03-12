# cloud-home


<details><summary>docker</summary>
<p>

#### We can hide anything, even code!

```bash
   1. Actualizar repositorios de Ubuntu Server
    - sudo apt update
    - sudo apt upgrade

  2. Instalar dependencias
    - apt install apt-transport-https ca-certificates curl software-properties-common -y

  3. Agregar repositorio de Docker
    - curl -fsSL https://download.docker.com/linux/ubuntu/gpg | apt-key add -
    - add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

  4. Instalar Docker y Docker Compose
    - sudo apt update
    - sudo apt install docker-ce docker-compose -y

  5. Activa el servicio de Docker
    - systemctl start docker
    - systemctl status docker
```

</p>
</details>

```
docker
  1. Actualizar repositorios de Ubuntu Server
    - sudo apt update
    - sudo apt upgrade

  2. Instalar dependencias
    - apt install apt-transport-https ca-certificates curl software-properties-common -y

  3. Agregar repositorio de Docker
    - curl -fsSL https://download.docker.com/linux/ubuntu/gpg | apt-key add -
    - add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

  4. Instalar Docker y Docker Compose
    - sudo apt update
    - sudo apt install docker-ce docker-compose -y

  5. Activa el servicio de Docker
    - systemctl start docker
    - systemctl status docker

kind
  - Crear Cluster : https://kind.sigs.k8s.io/docs/user/ingress/#create-cluster
  - ingress-nginx : https://kind.sigs.k8s.io/docs/user/ingress/#ingress-nginx
  - Hacer las pruebas de ejemplos

```