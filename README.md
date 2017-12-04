# ng1-exemplos
Definição O AngularJS é um framework JavaScript mantido pelo Google, que permite trabalhar com aplicações SPA (Single Page App). É orientado a dados, por meio de Data-Binding. Este framework é chamado na comunidade por Angular 1. A nova versão Angular 2 é totalmente diferente no modo de desenvolver, e utiliza tanto o NodeJS para aquisição dos módulos como TypeScript no desenvolvimento, enquanto que o Angular 1 (AngularJS) é totalmente baseado em JavaScript. A documentação do AngularJS pode ser encontrada em https://angularjs.org/



Rodando o servidor
Depois do Node.js ter sido instalado, dentro da pasta do projeto  que você descompactou anteriormente, busque todas as dependências do projeto através do seu terminal (prompt de comando, no caso do Windows) favorito com o comando.

npm install
ATENÇÃO USUÁRIOS DE WINDOWS: se por acaso mensagem de erro serem exibidas, procure pelo texto npm ERR! self signed certificate. Se ele existir, isso indica um problema no certificado do seu roteador (proxy). Não se preocupe, basta rodar o comando no terminal npm set strict-ssl false que resolvera este problema.

Em menos de um minuto, todas as dependências para rodar o servidor terão sido baixadas. Para subi-lo utilizamos o comando:

npm start
Repare que seu terminal ficará aguardando indefinidamente, sinal de que o servidor está escutando. Agora é só abrir o navegador no endereço http://localhost:3000. Uma página de boas-vindas será exibida.
