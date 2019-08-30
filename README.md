## heroku-buildpack-xpdf
This is xpdf buildpack for Heroku.

### Install
You can add buildpack like this. You can specify index number.
```
heroku buildpacks:add --index 3 https://github.com/matt-note/heroku-xpdf-buildpack.git
```

You can confirm buildpacks:
```
heroku buildpacks
```

You can remove this buildpack:
```
heroku buildpacks:remove https://github.com/matt-note/heroku-xpdf-buildpack.git
```
