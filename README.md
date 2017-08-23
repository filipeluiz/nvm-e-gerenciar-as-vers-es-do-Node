# NVM e gerenciar as versões do NodeJs 

O nvm(Node Version Manager) é um script que gerencia diferentes versões do Node.js

#Instalação

```
curl https://raw.githubusercontent.com/creationix/nvm/v0.23.2/install.sh | bash  
```

ou

```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.23.2/install.sh | bash  
```


![node.png](/home/filipe/Área de Trabalho/node.png)



pronto e agora vamos ver a versão atual

```
nvm current
```

instalar para a nova versão 8.4.x do Node.js e rodar

```
nvm install 8.4
```
Começar dar o apelido a versão 'nova'

```
nvm alias nova 8.4
```
![node2.png](/home/filipe/Área de Trabalho/node2.png)

se quiser usar a versão 8.x.x

```
nvm use nova
```

quer voltar a versão 6.x.x

```
nvm use 6
```

![node3.png](/home/filipe/Área de Trabalho/node3.png)

