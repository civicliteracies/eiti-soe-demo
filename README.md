# eiti-ose-demo

## WHat is it
Demonstration in a Jupyer notebook of the workflow to create a new companies database and API for EITI

## How do I use it

The prototype datasette is in the prototype-database folder. Cclone the repo then launch datasette using 

```shell
datasette EITI_Database.db -m metadata.json --template-dir=templates/ --static assets:static/
```

in order to load all the custom templates.