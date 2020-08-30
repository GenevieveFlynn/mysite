# Django App Tutorial - MySite

This is a project based off a Django tutorial to become more familiar with python. For more information, [read the documentation](https://docs.djangoproject.com/en/3.1/intro/tutorial01/). 

This application requires a secret key to run. This key can be generated through the Django shell or there are a number of websites which can generate one for you, [here is an example](https://djecrety.ir/). To generate from the command line, run the following prompts: 

`$ python manage.py shell`
```python 
>>> from django.core.management.utils import get_random_secret_key
>>> print(get_random_secret_key())
```
Copy the secret key and create a new secretkey.py file in the mysite directory. The file should look like below:  

`SECRET_KEY='paste_your_key_here'`

To run the project, enter 'python manage.py runserver' and navigate either to the [polls](http://127.0.0.1:8000/polls) or [admin sites](http://127.0.0.1:8000/admin) and enjoy! 
