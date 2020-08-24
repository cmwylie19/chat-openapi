# chat-openapi

## Develop against OpenAPI Spec
_Make sure you have ruby v2.7.1 installed, `rvm install 2.7.1`_   

Install `fakeit` with gem
```
gem install fakeit
```

### Return random responses
```
fakeit --spec openapi.yml -p 3333 --static-types
```

### Return Type Definitions
```
fakeit --spec openapi.yml -p 3333 --static
```

### Return example responses
```
fakeit --spec openapi.yml -p 3333 --use-example
```

