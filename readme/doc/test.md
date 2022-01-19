{% import "button/src/button.njk" as Button %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="/css/main.css" />
    <title>{{ title }}</title>
  </head>
  <body>
    {{ Button.btn('Hello Rioters 🤘 !') }}
    {{ content | safe }} 
  </body>
</html>
