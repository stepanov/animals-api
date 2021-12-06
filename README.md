# Test project - Animals API

## API Spec

API spec is created using OpenAPI 3.0.0 specification. It can be found in the *api* directory.

To build the API UI use following command:

```
$ redoc-cli bundle ./api/animals-spec.yaml -o animals-api-doc.html 
```

The live demo can be found <a href="https://stepanov.github.io/animals-api/animals-api.html">here</a>.

## Database schema

A database schema is created using Mysql Workbench. The source can be found in the directory 
*database*.
