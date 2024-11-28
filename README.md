# Simple Network

![Git](https://img.shields.io/badge/Git-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white) ![Bitbucket](https://img.shields.io/badge/Bitbucket-%230047B3.svg?&style=for-the-badge&logo=bitbucket&logoColor=white) ![NodeJs](https://img.shields.io/badge/Node.js-%23339933.svg?&style=for-the-badge&logo=node.js&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?&style=for-the-badge&logo=docker&logoColor=white) ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white) ![VSCode](https://img.shields.io/badge/VS_Code-%23007ACC.svg?&style=for-the-badge&logo=visual-studio-code&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?&style=for-the-badge&logo=mongodb&logoColor=white) ![Angular](https://img.shields.io/badge/Angular-%23DD0031.svg?&style=for-the-badge&logo=angular&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white) ![Typescript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?&style=for-the-badge&logo=typescript&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-%23FF6600.svg?&style=for-the-badge&logo=rabbitmq&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-%23D24939.svg?&style=for-the-badge&logo=jenkins&logoColor=white) ![Portainer](https://img.shields.io/badge/Portainer-%23007ACC.svg?&style=for-the-badge&logo=portainer&logoColor=white) ![OpenVPN](https://img.shields.io/badge/OpenVPN-%239600FF.svg?&style=for-the-badge&logo=openvpn&logoColor=white) ![ShellScript](https://img.shields.io/badge/Shell_Script-%234EAA25.svg?&style=for-the-badge&logo=gnu-bash&logoColor=white)

Lista de instalação dos softwares necessários para criação dos ambientes de desenvolvimento em máquinas Windows, Linux ou Mac. Alguns dos nomes dos softwares já possuem o link para download ou tutorial de configuração.

---

## Baixar e Instalar

- [ ] [Git 2.45.1^](https://git-scm.com/downloads)

- [ ] [Nvm 14.21.3](https://fabiojanio.medium.com/nvm-gerencie-m%C3%BAltiplas-instala%C3%A7%C3%B5es-do-node-js-6fcd0f13aaf7)

- [ ] [Docker Desktop](https://www.docker.com/products/docker-desktop/)

- [ ] [Java Open JDK 11](https://oracle.com/java/technologies/downloads/#/java11)

- [ ] [Visual Studio Code](https://code.visualstudio.com/Download)

- [ ] [OpenVPN Connect](https://openvpn.net/client/)

- [ ] [NoSqlBooster](https://nosqlbooster.com/downloads)

---

## Docker

No terminal executar o comando abaixo para baixar a versão correta do MongoDB para o container Docker.

```shell
docker run -d --name mongodb --restart always -p 27017:27017 -p 28017:28017 -e AUTH=no mongo:4.2.8
```

---

## Git

Crie uma pasta e clone os repositórios abaixo conforme o exemplo.

### sw-back

```shell
git clone https://x-token-auth:ATCTT3xFfGN0MNigx2ldqsi5ZlDX_NXYqn3dCLl_QzfZa2IwxUrTrtKD_2AQ6mI1izdfYEVKbrf-xe2PTFdd-S1suH7f4b28-9eEP2Aps487fDVWD3h0Xq55esZZOGorV35zHasUZ0UueAvyzM3LsbAEPAChFyRKoEqyTOZtZ0ouhnX1PWWBet0\=425AB261@bitbucket.org/gazetta/sw-back.git
```

```shell
cd sw-back
git checkout #SOLICITAR A BRANCH AO SUPORTE
npm install
npm start
```

> Dentro de **sw-back/scripts** execute `atualizaBibliotecas`

### sw-front

```shell
git clone https://x-token-auth:ATCTT3xFfGN0HyQmNntGazOQuxM8nEi9a5CCJl2xwytLWbb7VpjbUk0KRtL2qx1QdMqb-3Rl5HbvkbOvWuNBcwC5f83eiM-N-wGPU_mZUdayjW5R2waW_fV5quJsK9u17_FkW4Pq4hLqbPfWoASKUZdQIirh2CxMARto9ZfDjeifBj31Z16wRjw\=6648AB8D@bitbucket.org/gazetta/sw-front.git
```

```shell
cd sw-front
git checkout #SOLICITAR A BRANCH AO SUPORTE
npm install
npm start
```

> Caso no arquivo **src/environments/environment.ts** os parâmetros `apiUrl`, `wsUrl` e `promoUrl` não estiverem apontando para seu localhost, altere.


### campaign-processor

```shell
git clone https://x-token-auth:ATCTT3xFfGN0kHIVltahtzeOEPdq25CYAjxlD7RQz7wt0YHSdIfvuJtnGL9-_0dzlwUrk52rIaI7sg3KWS54sspiOtArTcrg1eamuHuod7d2YnKgWfLm8vjFGC_51xRkoOaeRAmazfekXFMR63wuEEh21q8XhxnJCBZHsenusoJYi1MBxeUdvx8\=7DB47826@bitbucket.org/gazetta/campaign-processor.git
```

```shell
cd campaign-processor/scripts
```

---

### VSCode

Na pasta em que foram baixados os repositórios **sw-front** e **sw-back** executar o comando `code .` incluindo o espaço e o ponto após o comando conforme o exemplo do quadro de código abaoxo:

```shell
code .
```
