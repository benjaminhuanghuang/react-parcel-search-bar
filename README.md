## Refercence
-[Let's build a search bar in React](https://www.iamtimsmith.com/blog/lets-build-a-search-bar-in-react/)

-[Parcel.js: Who says bundling needs to be difficult?](https://www.iamtimsmith.com/blog/parcel-js-who-says-bundling-needs-to-be-difficult/)


## Setup
```
yarn init -y
touch index.html app.js

npm i -S react react-dom 

npm i -D parcel @babel/core @babel/preset-env @babel/preset-react bulma 

touch .babelrc
```
- Parcel: A bundling library which requires no config
- @babel/preset-env:  tells Parcel how to transform ES6 to work with many different browsers
- @babel/preset-react: tells Parcel how to handle JSX
- Bulma: A CSS framework that uses flexbox and is easy to use. Link

Add start scripts in package.json
```
"scripts": {
    "start": "parcel index.html"
},
```