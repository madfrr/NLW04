# NLW04!

Repositório criado com o intuito de acompanhar e fazer anotações sobre a Next Level Week (NLW) da Rocketseat. A thread escolhida foi a de Node.js

## Aula 1

 - Alguns comandos úteis para inicialização de um projeto de Node.js com typescript e express.
	> yarn init -y
	>yarn add express
	>yarn add @types/express -D
	>yarn add typescript -D
	>yarn tsc --init
		>> Ir em tsconfig.json e mudar o "strict" de true para false
	>yarn ts-node-dev -D
		>>Ir no packege.json
		>>Logo abaixo do "license:" digitar 
	>>~~~javascript
	>>"scripts":{
	>> 	"dev": "ts-node-dev --transpile-only --ignore-watch node-modules src/server.ts"
	>>}
	>>~~~
 - Para iniciar o projeto, basta utilizar o seguinte comando no diretório ./API do projeto:
 ~~~powershell
		>>yarn dev
~~~

Explicando os comandos:

- **yarn init** serve para iniciar um projeto de node.js;
- O **add** serve para adicionar uma dependência;
- O sufixo **-D** serve para indicar que a dependência é apenas para desenvolvimento, ou seja, não vai ser utilizado em produção;
- O **tsc** é o typescript. Nosso projeto vai ser em typescript;
 - **ts-node-dev** é um "node" que transpila o typescript pra js e roda o projeto;
 