# Basic Flutter Template

...

## Directory Structure

The directory structure for this template is as follows:

```
.
├── auth
│   └── loaders.py
├── app.py
├── controller
│   ├── account.py
├── config.py
├── models
│   └── User.py
├── static
│   ├── css
│   │   └── style.css
│   ├── js
│   │   └── app.js
│   └── media
│       └── flask-icon.png
├── templates
│   ├── account
│   │   ├── home.jinja2
│   │   ├── sign_in.jinja2
│   │   └── sign_up.jinja2
│   ├── base.jinja2
│   └── index.jinja2
└── tests
    └── test_app.py
```

- `auth`: contains modules to auth configuration

## Getting Started

1. Clone this repository or download the ZIP file and extract it to a directory of your choice.
2. Install the required dependencies by running the command:
    ```shell
    pip install -r requirements-{environment}.txt
    ```
    > if environment is prd (production) it is setup to mysql database

3. Modify the configuration variables in app.py to fit your needs. For example, you may want to change the **SECRET_KEY** variable to a different value.
4. Modify the database schema in models/User.py to fit your needs. You can also create additional models if necessary.
5. Modify the routes in routes/account.py to fit your needs. You can also create additional blueprint modules if necessary.
6. Setup database and use the seeds (see [Setup](#setup))
7. Run the application by running the command `flask run` in your terminal.

## Setup

```shell
...
```

## Run

...

### Tests
   ```shell
   python3 -m unittest discover -s tests
   ```
## Features

...

### Conclusion

...
