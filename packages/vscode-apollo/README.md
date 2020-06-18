# Apollo GraphQL for VS Code

This is a fork of the official [Apollo GraphQL](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) extension that adds performance improvements for file watching and supports type parameters in gql tags:

```javascript
const employeesQuery = gql<"EmployeesQuery">`
  query employees {
    firstName
    lastName
  }
`;
```

