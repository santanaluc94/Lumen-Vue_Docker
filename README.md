# Docker Lumen/Vue

Projeto desenvolvido com fins de estudos de docker.

### Serviços do ambiente
- MySQL
- Apache
- phpMyAdmin
- PHP 7.4
- Lumen
- Node
- Vue

## Comandos

Para **instalar** todo o ambiente é necessário somente um passo:

```sh
bin/install
```

Para **parar** os contêiners do projeto:

```sh
bin/stop
```

Para **iniciar** os contêiners do projeto:

```sh
bin/start
```

Para **iniciar** os servidores do projeto, é só passar como parâmetro "lumen" ou "vue":

```sh
bin/run
```

> #### Executando o servidores:
> - _Sem argumentos_: Inicia os dois servidores locais sem atrelar o terminal
> - **lumen**: Inicia o servidor local do lumen atrelando o terminal
> - **vue**:Inicia o servidor local do vue atrelando o terminal

Para **entrar** no contêiner do projeto, é só passar como parâmetro "lumen" ou "vue":

```sh
bin/bash lumen
bin/bash vue
```

Para **reiniciar** os contêiners do projeto:

```sh
bin/restart
```

Para **deletar** o projeto:

```sh
bin/kill
```

> Este comando inclui as seguintes funções:
> - deletar o lumen
> - deletar o vue
> - deletar o node
> - deletar o banco de dados
> - deletar os contêiners
> - deletar o volume do contêiner
> - deletar a rede dos contêiners

---

## Acessos

### MySQl

Acessos do banco de dados como administrador:

```txt
Usuário: admin
Senha: admin1234
```

Os endereços de IP do MariaDB:

```txt
padrão: 171.0.0.10:3306
local: 127.0.0.1:3306
```

### phpMyAdmin

O acesso ao phpMyAdmin já vem por padrão o usuário de administrador do banco de dados.
Os endereços de IP do phpMyAdmin:

```txt
padrão: 171.0.0.15:80
local: 127.0.0.1:8000
```

### Lumen

Os endereços de IP do Lumen:

```txt
padrão: 171.0.0.20:80
local: 127.0.0.1:80
```

### Vue

Os endereços de IP do Vue:

```txt
local: 127.0.0.1:8080
```