# Jenkins

  ### Sobre a ferramenta:
Jenkins é uma ferramenta para CI/CD.
  

# Instalação
A aplicação é inteiramente gerenciada pelo Docker, então é imprescindível ter o mesmo instalado.

## 1) Primeiro passo:

    docker-compose up -d

## Após subir o Container digite: docker-compose ps

    Name         Command     State        Ports                      
    ----------------------------------------------------------
    jenkins   /sbin/tini -- /usr/local/b ...   Up      0.0.0.0:50000->50000/tcp, 0.0.0.0:8081->8080/tcp   


nesse momento a stack do docker-compose já estará no ar.

e agora você poderá visualizar a aplicação na rota abaixo:

[http://localhost:8081/](http://localhost:8081/)


> Escrito por: Leonardo Ribeiro em 23 de Dezembro de 2020.
