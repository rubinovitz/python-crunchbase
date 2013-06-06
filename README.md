crunchbase
==========
 
This is a Python Library for the Crunchbase API. So far the only change to the originally library is to add the Mashery API key into the queries so they are allowed by the Crunchbase API. Also, the class name was started with an uppercase letter to conform to PEP standards.

You can get an API key [here](http://developer.crunchbase.com/apps/register) once you have a Mashery Account.


Dependency
----

This Library needs the simplejson library that can be downloaded
from http://pypi.python.org/pypi/simplejson/

API Documentation
----

These are the original docs:
http://groups.google.com/group/crunchbase-api/web/api-v1-documentation

The only change is to instantiate the Crunchbase class you must now pass in your API key. For example:

```
from crunchbase import Crunchbase

c = Crunchbase("YOUR_KEY") 
print c.getCompanyData("square") # get the company data for square
```

