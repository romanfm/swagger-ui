# Swagger UI (yaml)

Changes to support yaml based specs. 

Added library form `lib`

```javascript
  <script src='lib/swagger-oauth.js' type='text/javascript'></script>
```

Replaced default url `http://petstore.swagger.io/v2/swagger.json` for local file `swagger.yaml` in `dist/index.html`

```javascript
      if (url && url.length > 1) {
        url = decodeURIComponent(url[1]);
      } else {
        url = "/swagger.yaml";
      }
```

