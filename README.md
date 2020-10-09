# WhatsApp Chatbot - Node.js

Esse é um chatbot para WhatsApp feito exclusivamente para a disciplina de "Algoritmos Avançados" do professor Hilson Silva da Estácio Teresina. 

O objetivo desse bot é simular o atendimento online de uma pizzaria. Por hora, só possui armazenamento estático de dados, logo, é só um algoritmo.


### Instalação

- Nosso chatbot requer [Node.js](https://nodejs.org/) v12.x.x+ para rodar

Entre na pasta do projeto:
```sh
$ cd nodebot-wpp
```

Instale as dependências:
```sh
$ npm install
```
Logo após instalar as dependências, basta dar um:
```sh
$ npm start
```

### Conexão
Assim que a aplicação iniciar, aparecerá um Código QR para que você possa fazer o vínculo com um WhatsApp (o do estabelecimento que quer que seja automático). Deverá aparecer a seguinte mensagem no terminal:
```sh
Scan QR for Session: session
```

Para isso, basta no aplicativo do WhatsApp em seu smartphone, ir na opção de WhatsApp Web e fazer a leitura do código. Assim que a autenticação for feita com sucesso no BOT, ele deve mostrar uma sequência de mensagens semelhante a essas no terminal:
```sh
✓ Authenticated
✓ headless option is active, browser hidden
✓ Starting With Success!
✓ Token saved successfully...
```

Agora, basta mandar a mensagem de algum outro celular para o WhatsApp que você cadastrou que ele deverá responder com a lógica implementada no código!

### Plugins 
Utilizamos apenas o plugin `venom-bot` para fazer a conexão com o WhatsApp para a execução do chatbot.

| PLUGIN | REPOSITÓRIO | 
| ------ | ------ |
| Venom-bot | [IR AO REPOSITÓRIO](https://www.npmjs.com/package/venom-bot) |

### Créditos
Projeto desenvolvido por alunos do curso Ciência da Computação da Faculdade Estácio Teresina.

| ALUNO | MATRICULA |
| ----- | --------- |
| Raquel Martins Nunes | 201908343222
| Artur Vinicius Delmiro Lacerda | 201908606568
| Alexandre Igor Noia Lacerda Silva | 201908412534
| Pedro Emmanuel Dias Medeiros | 201908354399
| Marcus Vinicius Silva Souza | 201908354356
| Vitor Kassiel Araujo Almeida | 201908354488

