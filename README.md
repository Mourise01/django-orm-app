# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

### STEP 2:

### STEP 3:

Write your own steps

## PROGRAM

```python
from django.db import models
from django.contrib import admin
# Create your models here.
class employement(models.Model):
    employementnumber = models.IntegerField()
    employementname = models.CharField(max_length=100)
    age = models.IntegerField() 
    email = models.EmailField()
    place = models.CharField(max_length=100)
    designation = models.CharField(max_length=100)
    salary = models.CharField(max_length=100)
class EmployementAdmin(admin.ModelAdmin):
    list_display = ('employementnumber','employementname','age','email','place','designation','salary')
```

## OUTPUT
![output](./imasge/Screenshot%20from%202023-01-20%2009-36-19.png)




## RESULT
