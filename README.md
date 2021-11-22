# javalin-cors-example

## fixing cors issue

There was a cors issue for following situation

`ui (http://localhost:8081/ui) --> backend (http://localhost:80/api)`

issue : https://github.com/tipsy/javalin/issues/1433

suggested solution (adding trailing slash on client side) solves this issue!

Thx @Playacem