ISSUE:
- Logged data is not in the expected order when using context.log
```
context.log("one")
context.log("two")
context.log("three")

// expectation is
one
two
three

// result varies in order instead
```


To install packages
`npm i`

To start
`npm run dev`

To call the function / trigger the issue
`curl --location 'http://localhost:7071/api/test'`