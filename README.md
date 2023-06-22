![Integrando seu projeto React com APIs](thumbnail.png)

# AluraBooks

O AluraBooks é uma loja virtual que vende livros da Casa do Código. 
É um MVP que tá só começando e ainda tem muitas funcionalidades novas para serem desenvolvidas.

<img src="screencapture.png" alt="Imagem do AluraBooks" width="50%">


## 🔨 Funcionalidades do projeto

O AluraBooks começa com a página inicial já pronta, que você pode baixar e utilizar ou então... criar a sua versão baseada <a href="https://www.figma.com/file/POpX503Kobu83iGdiaICvk/React%3A-Alura-Books?node-id=119%3A3145" target="_blank">no figma</a>.
No decorrer da formação nós vamos implementar toda a camada de comunicação com a API, inclusive a autenticação.

## ✔️ Técnicas e tecnologias utilizadas

Se liga nessa lista de tudo que usaremos nessa formação:

- `React`
- `React Hooks`
- `TypeScript`
- `axios`
- `Session Storage`
- `TSDX`
- `NPM` (no primeiro curso nós criamos uma biblioteca e a publicamos no NPM)
- `Github Actions`

E muito mais!

## 🛠️ Abrir e rodar o projeto

Para abrir e rodar o projeto, execute `npm i` para instalar as dependências e `npm start` para inicar o projeto.

Depois, acesse <a href="http://localhost:3000/">http://localhost:3000/</a> no seu navegador.

## 📚 Mais informações do curso

O AluraBooks é o projeto utilizado durante toda a formação, e você pode navegar entre as branchs para encontrar o momento específico que está buscando.

## HTTP

O HTTP é um protocolo da camada de aplicação do modelo OSI. Por falar em protocolo, de maneira análoga, um protocolo é uma conversa entre cliente-servidor.

> Exemplo de funcionamento

<img src="arquiteturaHTTP.png" alt="HTTP" width="100%">

## Portas padrão

|Portas padrão|Nome|
|-------------|----|
|80|Padrão HTTP|
|443|Padrão HTTPS|
|De 1023* até 65535|Livres para uso|

> Portas  entre 0 e 1023 são reservadas para serviços padronizados


## Postman

Desdrição:

### Sobre o servidor

O servidor não lembra dos estados que ele possuiu, mas existem formas de ficar lembrando ele que são:

- Sessão --> Tempo que o usuário fica logado 

- Cookies --> São mecanismo do HTTP que a gente utiliza lá nos headers do HTTP para que o servidor peça
que o cliente salve algumas informações que vão ser utilizada depois para lembrar o servidor novamente.


## Documentação do protocolo HTTP

> Link - https://www.rfc-editor.org/rfc/rfc7231

Cada início de número quer dizer um tipo de status request

 6.2. Informational 1xx .........................................50
           6.2.1. 100 Continue .......................................50
           6.2.2. 101 Switching Protocols ............................50
      6.3. Successful 2xx ............................................51
           6.3.1. 200 OK .............................................51
           6.3.2. 201 Created ........................................52
           6.3.3. 202 Accepted .......................................52
           6.3.4. 203 Non-Authoritative Information ..................52
           6.3.5. 204 No Content .....................................53
           6.3.6. 205 Reset Content ..................................53
      6.4. Redirection 3xx ...........................................54
           6.4.1. 300 Multiple Choices ...............................55
           6.4.2. 301 Moved Permanently ..............................56
           6.4.3. 302 Found ..........................................56
           6.4.4. 303 See Other ......................................57
           6.4.5. 305 Use Proxy ......................................58
           6.4.6. 306 (Unused) .......................................58
           6.4.7. 307 Temporary Redirect .............................58
      6.5. Client Error 4xx ..........................................58
           6.5.1. 400 Bad Request ....................................58
           6.5.2. 402 Payment Required ...............................59
           6.5.3. 403 Forbidden ......................................59
           6.5.4. 404 Not Found ......................................59
           6.5.5. 405 Method Not Allowed .............................59
           6.5.6. 406 Not Acceptable .................................60
           6.5.7. 408 Request Timeout ................................60
           6.5.8. 409 Conflict .......................................60
           6.5.9. 410 Gone ...........................................60
           6.5.10. 411 Length Required ...............................61
           6.5.11. 413 Payload Too Large .............................61
           6.5.12. 414 URI Too Long ..................................61
           6.5.13. 415 Unsupported Media Type ........................62
           6.5.14. 417 Expectation Failed ............................62
           6.5.15. 426 Upgrade Required ..............................62
      6.6. Server Error 5xx ..........................................62
           6.6.1. 500 Internal Server Error ..........................63
           6.6.2. 501 Not Implemented ................................63
           6.6.3. 502 Bad Gateway ....................................63
           6.6.4. 503 Service Unavailable ............................63
           6.6.5. 504 Gateway Timeout ................................63
           6.6.6. 505 HTTP Version Not Supported .....................64

## Baixando o openssl

O openssl é um programa de criptografia que permite entre outras coisas gerar chaves privadas e certificados digitais.

> Link para dowunload `https://slproweb.com/products/Win32OpenSSL.html`