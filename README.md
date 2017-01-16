# EcmaStack GraphQL Starter Kit
---

## Getting started

1. `npm install`

2. `npm start`

3. If your terminal reads "Running a GraphQL API server at localhost:4000/graphql"
you are in good shape.  Navigate to `localhost:4000/graphql` and the graphiql
interface should render.

4. Test writing the following query in the left hand window:

```javascript
{
  hello
}
```

The right window should yield:

```javascript
{
  "data": {
    "hello": "Hello world!"
  }
}
```

Now, you are off to the races!

### Possible issues

This project was built using Node 6.x.x.  Please check to make sure that
your engines match those specified in `package.json`.
