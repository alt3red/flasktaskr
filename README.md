# flasktaskr
## * a flask task app from Real Python book 2 *

### Configuration
A _config.py file is required with the following:

`import os`

`basedir = os.path.abspath(os.path.dirname(__file__))`

`DATABASE = ''`

`WTF_CSRF_ENABLED = True`

`SECRET_KEY = ''`

`DATABASE_PATH = os.path.join(basedir, DATABASE)`

