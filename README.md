## Node.js with MongoDB Example

<img src=https://i.imgur.com/eDNZeqh.png alt='Swagger Page of that application' title='Swagger Page of that application'/>

### Requirements

* Node.js v7+
* MongoDB running on local instance

### Running

* Install dependencies - `npm i`
* Build typescript - `npm run build`
* Run project - `npm start`
* Go to swagger page - `localhost:3000/documentation`

### Criar imagem docker
* docker build -t api-herois .
* docker run -p 3000:3000 --link mongodb:mongodb -e MONGO_URL=mongodb api-herois
* docker run -d --name mongodb mongo:3.5
