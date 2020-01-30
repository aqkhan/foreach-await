
# Await inside forEach

A better forEach loop for your javascript applications with await capability. 

# Install
```
npm install [--save] @alphasquad/foreach-await

// OR

npm i [-S] @alphasquad/foreach-await
```

# Usage

For ECMA < ES6

```
const forEach = require('@alphasquad/foreach-await')

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
import forEach from '@alphasquad/foreach-await'

forEach(arr, async(item) => {
    await doSomething(item)
})

// To await the entire loop

await forEach(arr, async(item) => {
    await doSomething(item)
})

```
