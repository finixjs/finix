# finix

A __HTTP__ library for __Node.js__ and __Browser__.

It is both __Promise__- and __Observable__-based.

# Install

__NPM:__
```sh
npm i finix -S
```

__Yarn:__

```sh
yarn add yarn
```

# Usage

Using Promise:

```js
const finix = require('finix')

finix.get('').then((v)=>{
    v.json()
}).error((err)=>console.log(err))
```

Using Observable:

```js
const finix = require('finix')

finix.get('').subscribe((v)=>{},err=>console.log(err))
```
