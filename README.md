# projetos-nasa-br
projeto simples em apenas html e uma imagen docker do nginx 

- instale o docker e compose
- crie uma imagen com o comando " docker build . -t fsthiago/proj_uni:1.0 "
- execute o container definindo "--name", modo daemon "-d", porta "-p" e "image id"
- "docker run --name proj_vcdefine -d -p 8080:80 image-id/nomecontainer"
