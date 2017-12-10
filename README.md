# vuejs-expressjs
a vuejs/expressjs web application
# client front-end vuejs
npm install -g vue-cli
vue list
vue init webpack client
npm install
npm run dev
# server back-end expressjs
mkdir server

npm init -f //package.json uusgeh
npm install --save nodemon eslint
node ./node_modules/eslint/bin/eslint.js --init
packages.json add scripts->
    "start": "node node_modules/nodemon/bin/nodemon.js src/app.js --exec",
    "lint": "node node_modules/.bin/eslint **.*.js"
npm start
npm install --save express body-parser cors morgan
