
# Await inside forEach

A better forEach loop for your javascript applications with await capability. 

# Install
```
npm install [--save] foreach-await

// OR

npm i [-S] foreach-await
```

# Usage

For ECMA < ES6

```
const forEach = require('foreach-await')

forEach(arr, async(item) => {
    await doSomething(item)
})

// To await the entire loop

await forEach(arr, async(item) => {
    await doSomething(item)
})

```

For ECMA > ES6

```
import forEach from 'foreach-await'

forEach(arr, async(item) => {
    await doSomething(item)
})

// To await the entire loop

await forEach(arr, async(item) => {
    await doSomething(item)
})

```
