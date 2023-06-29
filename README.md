1.

> Using JavaScript, write a function that accepts a string and logs it.

2.

> Add the JavaScript code that iterates through each of these words using a `for` loop and concatenates them into a sentence. Don't forget to add spaces!

```js
const words = ["The", "quick", "brown", "fox"]
let sentence = ""

// Your code here

console.log(words)
```

3.

> Using `.filter()` and `.forEach()`, add the necessary JavaScript to print out only the 2 even numbers, such as:

```
2
4
```

```js
const numbers = [{
  content: 1,
},{
  content: 2,
},{
  content: 3,
},{
  content: 4,
},{
  content: 5,
}]
```

4.

> Write the Node.js code that imports the `writeFile` function from the `fs/promises` module using either ESM or CommonJS syntax. Invoke it with the arguments `"README.md"` and `"utf8"`, which will evaluate to a promise. Print the result of the resolved promise to the console.

5.

> Add appropriate TypeScript types to these declarations:

```ts
let someNumber
let someString
let someBoolean
```

6.

> Write a TypeScript function that accepts a two strings and returns whether the first string contains the second.

7.

> Write a type for the following object:

```ts
const someObject = {
  someArray: [{
    someNumber: 42,
    someBoolean: true,
  },{
    someNumber: 99,
    someBoolean: false,
  }]
}
```

8.

> Add the type `User` as a generic to the `.get()` call:

```ts
type User = {
  username: string;
}

axios.get(`${process.env.BASE_URL}`/users/1)
  .then(response => {
    console.log(response.data)
  })
```

9.

> Describe Node as best you can.

10.

> Describe RESTful APIs as best you can.

11.

> Write the shell code to install the npm modules `supertest` and `knex`.

12.

> Write the code to respond to any `GET` request to the root of the server with the following JSON:

```json
{
  "message": "Hello, world!"
}
```

```ts
import express from "express"

const app = express()
```

13.

> Add the TypeScript needed to connect to a database at "mysql://localhost:3306". Then, add a route that responds to `POST` requests at `/posts` and pulls an object out of the body. Insert the `post` value of the object into the `content` column of the `post` table.

```ts
import express from "express"
import knex from "knex"

const app = express()

const config = {
}

const database = knex()

const PORT = 3000
app.listen(PORT)
```

14.

> Write the Jest code to assert that `getHelloWorld` returns `"Hello, world!"` when invoked.

```ts
import {test} from "jest"

const getHelloWorld = () => "Hello, world!"

test() // Your code here
```

15.

> Write code to assert the basic behavior of the `transformAll` function.

```ts
import {test} from "jest"

const transformAll = (
  words: string[],
  transformation: (word: string) => string,
) => transformation(word)

test() // Your code here
```

16.

> Using Supertest and Jest, assert that a request to `/users/1` returns 200 and return the JSON `{ "username": "sikaeducation"}`:

```ts
import { test } from "jest"
import request from "supertest"
import app from "./app"

// Your code here
```

