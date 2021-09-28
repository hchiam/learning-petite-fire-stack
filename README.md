# Learning "petite fire stack" [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://github.com/hchiam/learning-template/blob/main/LICENSE)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

<https://www.youtube.com/watch?v=Sxxw3qtb3_g>

<https://github.com/vuejs/petite-vue>

Deps:

- petite-vue (no virtual DOM, no redux)
- bootstrap (no CSS post-processing)
- ionic (for mobile)
- firebase (firestore = DB, authentication) (so no need for webserver or cache)
- firebase cloud function (for serverless server-side code) (no need to think about docker, kubernetes, or terraform)

Other notes:

- (use script tags, so no module bundler like webpack)
- (no CI/CD until you need to test and redeploy every day)
- (no graphql until you need to stitch multiple APIs together)

```html
<html>
  <head>
    <script src="https://unpkg.com/petite-vue" defer init></script>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css"
      integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU"
      crossorigin="anonymous"
    />
    <script
      type="module"
      src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.esm.js"
    ></script>
    <script
      nomodule
      src="https://cdn.jsdelivr.net/npm/@ionic/core/dist/ionic/ionic.js"
    ></script>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/@ionic/core/css/ionic.bundle.css"
    />
    <script src="https://www.gstatic.com/firebasejs/8.2.7/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.2.7/firebase-firestore.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.2.7/firebase-auth.js"></script>
  </head>
  <body></body>
</html>
```
