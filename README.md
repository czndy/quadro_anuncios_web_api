# Para criar o backend:

(Caso não tenha o yarn instalado, digite o código abaixo no CMD)
```
npm install --global yarn
yarn --version
```


Crie uma pasta com o nome desejado

Shift+Clique com botão direito

Abrir janela do PowerShell aqui (ou CMD)
```
yarn init -y
yarn add express
yarn add nodemon -D
yarn add cors
```

# Iniciar servidor:
## Abra o terminal no VSCode (Ctrl + aspa) e digite o seguinte comando
```
node src/server.js
```

No navegador, abra localhost:5000

Para parar o servidor, aperte no teclado Ctrl+C


## Observação:
- Será feito automaticamente o deploy de qualquer alteração commitada pro backend.
- Por isso, o ideal seria se o commit só fosse feito com a aplicação em um estado estável.

## Deploy feito em:
https://dashboard.heroku.com/apps/quadro-anuncios-web-api/deploy/github
## URL da API: 
https://quadro-anuncios-web-api.herokuapp.com/
