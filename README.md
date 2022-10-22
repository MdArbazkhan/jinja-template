### jinja template engine
Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax.

Most of the time we use jinja template along with django or flask. Here I have tried to just work with jinja template with json to dynamically load the data to the output page.

Here I have used JInja-cli to export the html file which we can render on browser. Jinja-cli takes the json file and pass it to jinja template and based on logic written inside jinja template, it loads the data.

Here's the command to export jinja template to html file with the help of jinja-cli
```
jinja -d data.json -o result.html  jinja_template.j2
```
And here is the screenshot of the html page.
