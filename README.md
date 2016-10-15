# Swagger UI (yaml)

Changes in `src/main/html/index.html` to support yaml based specs. 

Added parser library `js-yaml`

```javascript
  <script src='lib/swagger-oauth.js' type='text/javascript'></script>
```

Replaced default url `http://petstore.swagger.io/v2/swagger.json` for local file `/specs/wagger.yaml`

```javascript
      if (url && url.length > 1) {
        url = decodeURIComponent(url[1]);
      } else {
        url = "/specs/swagger.yaml";
      }
```
