# TS-Expressjs
 1-Inciamos repo npm
 npm init --yes
2- Instaamos express
npm install express
3-Instalamos ts y los types de express
npm i -D typescript @types/express @types/node
4- Creamos el archivo tsconfig.conf
npx tsc --init
5- Creamos el archivo gitignore
node_modules
dist
6- Agregamos dos Scripts en el archivo package.json
    "scripts": {
    "build": "npx tsc", (npm run build)
    "start": "node dist/index.js" (npm run start)
  },
