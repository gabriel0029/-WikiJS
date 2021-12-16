# Preparação do ambiente

### Instalação Docker
```
 curl -fsSL https://get.docker.com/ | sh
```
Obs: Instalará a versão mais recente.

### Instalação o Kind
```
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.11.1/kind-linux-amd64
chmod +x ./kind
mv ./kind /usr/local/bin/kind
```
### Instalação o Kubectl
```
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
```

## Caso use o docker compose
### instalação 
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

### Primeiro acesso
Acesse em seu navegador http://ip_de_seu_servidor. Será carregado a página para a criação da conta de administrador, preencha os dados exigidos e clique e install para proceguir.

![Captura de tela de 2021-12-16 09-46-53](https://user-images.githubusercontent.com/87427032/146380846-5c95805a-09dd-4058-884c-d1ffa09a26d8.png)


### Criando a primeira página.

Faça o logon na página 
![Captura de tela de 2021-12-16 09-48-07](https://user-images.githubusercontent.com/87427032/146381133-71d47475-1fad-4d1c-a9a0-60a1d8613972.png)

Após o logon, será apresentado a tela de boas vindas, que também já trará a opção de criar sua primeira página.
![Captura de tela de 2021-12-16 09-48-16](https://user-images.githubusercontent.com/87427032/146381192-1b06125f-1fa6-43f1-874b-2babcf6e1d70.png)


