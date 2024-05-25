<h1 align="center"> BasicNodejsType </h1>
O basico para instalar nodejs e typescript com compilaçao e bibliotecas.

## Configuracao

:computer: Instalar o nodejs LTS via link: https://nodejs.org/en. :computer:

Caso precise validar a versa od onode : node -v
   
1.  Criar uma pasta : mkdir <nomeprojeto>
2.  Abrir o editor de sua preferencia.
3.  Rodar npm init -y para criar o pck.json
4.  Instalar o typescript @types/node -D Instalar as dependencias
5.  Instalar a biblioteca tsx -D para rodar os arquivos .ts sem precisar converter para .js
6.  npx tsc --init cria o tsconfig.json
7.  Acessar o repositorio do Node target Mapping : https://github.com/microsoft/TypeScript/wiki/Node-Target-Mapping
8.  criar a pasta exemplo: src > http.
9.  criar um arquivo service.ts
10. alterar o arquivo pck.json, adicionando o seguinte campo:
```
    -   "scripts": {
          "dev": "tsx watch src/http/server.ts"
        },
```
11. Executar o comando npm run dev


## Rodar o projeto

:computer: Após baixar o repositório, instalar suas dependencias através do comando: npm install. Após isso seguir o passo 11 :computer: