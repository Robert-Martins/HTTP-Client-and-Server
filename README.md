# HTTP-Client-and-Server

<img src="https://img.shields.io/badge/Status-Concluded-green" /> <img src="https://img.shields.io/badge/Version-1.0.0-green" />

<br>

Este projeto consiste no desenvolvimento de um cliente HTTP utilizando JavaScript puro (Vanilla JS) que consome um servidor HTTP desenvolvido em Java 18 utilizando Jetty Servlet.

### Objetivo do desenvolvimento do projeto

O objetivo deste projeto é ilustrar a comunicação entre um cliente HTTP e um servidor HTTP, reforçando conceitos como:

- Manipulação de requisições HTTP
- Criação de servidores utilizando Jetty Servlet
- Consumo de APIs utilizando JavaScript
- Desenvolvimento em Java e JavaScript

### Tecnologia utilizada no desenvolvimento do projeto

<img src="https://skillicons.dev/icons?i=java,js" width="60" height="60" />

<br>

### Como acessar meu projeto?

Para ter acesso ao código, basta clonar o projeto ou baixá-lo em formato ZIP.

Para executar o servidor, é necessário ter o JDK 18 instalado. O cliente pode ser executado em qualquer navegador moderno. Siga as instruções abaixo:

1. **Servidor**:
   - Navegue até o diretório do projeto no terminal.
   - Compile e execute o servidor utilizando sua IDE preferida ou via linha de comando.
   - O servidor estará disponível na rede local conforme a configuração em código.

2. **Cliente**:
   - Abra o arquivo HTML do cliente em um navegador.
   - Insira o IP da máquina que hospeda o servidor no código JavaScript do cliente (`requestUrl`).

### Detalhes sobre a execução

O servidor estará disponível para acesso na rede local da máquina. O cliente não precisa ser necessariamente acessado pela mesma máquina que hospeda o servidor. Para isso, insira o IP da máquina que hospeda o servidor no código JavaScript do cliente:

```javascript
const requestUrl = 'http://<your-network-ip>';
```

### Posso contribuir em seu projeto?

Claro, toda participação é bem-vinda.

Para realizar implementações, basta criar branches com o nome da feature a ser implementada ou da correção a ser realizada. Em seguida, solicitar merge requests para a branch develop.

### Seguimento do projeto

O projeto está concluído. Contudo, à medida que eu visualizar possíveis melhorias ou novas features, este projeto será atualizado.

### Licença do projeto

MIT license
