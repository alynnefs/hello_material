# hello_material

Exercício Angular + Angular material

- criar projeto npm client-side (é que nem um projeto npm normal, só que roda no browser)
- usar angular e angular-material. instalar via npm e salvar a dependência no package.json
- devemos simular uma tela de login
- o botão de login deve subir um alert dialog similar a este: https://material.angularjs.org/HEAD/demo/dialog
- o código deve ser "compilado" com browserify
- opcionalmente, os css necessários devem ser importados com o browserify-css: https://www.npmjs.com/package/browserify-css
  Caso deseje não usar o transform acima, basta colocar os css referenciados no index.html
- o javascript construído pelo browserify deve se chamar build.js
- o servidor de prototipação budo deve constar num npm script. Batize o script como dev (para rodar com npm run dev)
- a interface da tela de login deve fazer uso dos estilos e componentes do angular-material: https://material.angularjs.org/HEAD/demo/input#errors
- a caixa de login deve ser um panel centralizado no meio da tela. faça uso das estratégias de layout do angular-material para conseguir isso: https://material.angularjs.org/HEAD/layout/alignment
- A entrega é um repositório git onde se possa fazer clone, executar npm run dev na linha de comando e o budo executar um servidor e abrir a tela solicitada automaticamente


- npm init
- npm install angular --save
- npm install angular-material --save
- npm install browserify budo --save-dev
- sudo npm install budo --save -g
- budo src/main.js -o
- browserify src/main.js -o build.js
