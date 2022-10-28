# django-demo
Django Tutorial output


## build image

```
pack build django-demo --builder heroku/buildpacks:20
```

## run image

```
docker run --rm -p 8000:8000 django-demo 
```
