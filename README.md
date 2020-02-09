### Blog Backend

#### Start

```bash
npm start
```

#### Nest.js Concept

- Dependency Injection
  
  Inject services into controller

  ```ts
  @Controller('blog')
  export class BlogController {

    constructor(private blogService: BlogService) { }

    ...
  
  }
  ```