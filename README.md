# reactive-programming-rxjs-lab

## Install RxJS 4

```bash
npm install rx
npm install -g rx
```

## Install Json Server
https://github.com/typicode/json-server

```bash
npm install -g json-server
```

## City API

```bash
$ json-server --watch data/cities.json --port 8080 --routes cities-routes.json
or
$ npm run city-service
```

```
Search cities with inseeCode=77243
http://localhost:8080/api/city/77243

Get all cities
http://localhost:8080/api/cities

Search cities with postcode=77400
http://localhost:8080/api/cities?postcode=77400
```

## Pokemon API

```bash
$ json-server --watch data/pokemons.json --port 8080 --routes pokemons-routes.json
or
$ npm run pokemon-service
```

```
Search pokemon with index=25
http://localhost:8080/api/pokemon/25

Get all pokemons
http://localhost:8080/api/pokemons

Search pokemon with French name Roucool
http://localhost:8080/api/pokemons?fr=Roucool
```

## Install Node-fetch

```bash
$ npm install --save-dev node-fetch
```

## Install Crazymail

https://github.com/koopero/crazymail

npm install -g crazymail
npm install --save-dev crazymail


## Reactive Manifesto

http://www.reactivemanifesto.org/


## Learn functional programming in JavaScript

http://reactivex.io/learnrx/

