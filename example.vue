<!DOCTYPE html>
<html>
  <head>
    <title>Vue.js CDN</title>
    <script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js">
    </script>
    <script>
      document.addEventListener('DOMContentLoaded', function () {
        new Vue({
          el: '.reactive-text',
          data: {
            text: "Start using Vue.js today!"
          }
        })
      })
    </script>
  </head>

  <body>
    <div>
      <p class="reactive-text">{{ text }}</p>
    </div>
  </doby>

</html>