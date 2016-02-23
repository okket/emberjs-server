#Extremly simple Express scaffold for Ember

Credits: http://www.programwitherik.com/setup-your-ember-project-with-node/

Usage:

Do not clone into your Ember app directory, use a separate directory.
From your Ember app directory build into the server public dir, example:

```ember build --environment=production --output-path=../server/public/```

Start Express in the server directory with

```node server.js```

You should be able to access your Ember app on http://localhost:3000/

Alternatives:

* https://github.com/mholt/caddy/
* ```python -m SimpleHTTPServer 3000```
* Free static hosting service like surge.sh
* ...
