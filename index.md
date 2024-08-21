# Encabezado mamalon

### Sub encabezado

Ejercicio de Markdown

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

JavaScript Code
``` javascript
var express = require('express');
var router = express.Router();

/* GET home page. */
router.get('/', function(req, res, next) {
  res.render('index', { title: 'Express' });
});

module.exports = router;
```

Python Code
``` python
from django.db import models
from django.contrib.auth.models import User

# Create your models here.


class Category(models.Model):
    slug = models.SlugField(max_length=255)
    title = models.CharField(max_length=255)

    def __str__(self):
        return self.title
```
