# Babel
Babel is a JavaScript compiler.
Use next generation JavaScript, today.

Instalação do babel :
```
npm install @babel/cli @babel/core @babel/preset-env
```
Copilar um codigo ES6,7,8 JS para versões de navegadores antigos.

```
npx babel index.js -o bundle.js --presets=@babel/env
```

Adicionar a compilação do codigo para versões antigas no arquivo package.json
```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "babel": "babel index.js -o bundle.js --presets=@babel/env -w"
  },
```

Copilar com npm

```
npm run babel
```