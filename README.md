# Simple Network

Lista de instalação dos softwares necessários para criação dos ambientes de desenvolvimento em máquinas Windows. Alguns dos nomes dos softwares já possuem o link para download ou tutorial de configuração.

---

## Baixar e Instalar

- [ ] [Git 2.40.1^](https://github.com/git-for-windows/git/releases/download/v2.40.1.windows.1/Git-2.40.1-64-bit.exe)

- [ ] [Node 12.18.0](https://fabiojanio.medium.com/nvm-gerencie-m%C3%BAltiplas-instala%C3%A7%C3%B5es-do-node-js-6fcd0f13aaf7)

- [ ] [Docker Desktop](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe)

- [ ] Java Open JDK 11

- [ ] [Visual Studio Code](https://code.visualstudio.com/docs/?dv=win)

- [ ] [OpenVPN Connect](https://openvpn.net/downloads/openvpn-connect-v3-windows.msi)

- [ ] [NoSqlBooster](https://s3.nosqlbooster.com/download/releasesv8/nosqlbooster4mongo-8.0.9.exe)

---

## Docker

No terminal do Windows (MS-DOS) executar o comando abaixo para baixar a versão correta do MongoDB para o container Docker.

```shell
docker run -d --name mongodb --restart always -p 27017:27017 -p 28017:28017 -e AUTH=no mongo:4.2.8
```

---

## Git

No terminal do Windows (MS-DOS) executar o clone dos repositórios.

### sw-back

```shell
git clone https://wmarcondesbr@bitbucket.org/gazetta/sw-back.git
```

```shell
cd sw-back
git checkout manoel-teste
npn install
npm start
```

### sw-front

```shell
git clone https://wmarcondesbr@bitbucket.org/gazetta/sw-front.git
```

```shell
cd sw-front
git checkout manoel-teste
npn install
npm start
```

---

### VSCode

Na pasta em que foram baixados os repositórios **sw-front** e **sw-back** executar o comando `code .` incluindo o espaço e o ponto após o comando conforme o exemplo do quadro de código abaoxo:

```shell
code .
```
