# Flask project start template

### About
Includes:
- Flask ready app with proper structure :)
- SQLAlchemy
- Flask-Migrate
- SQLite


### Structure
```
.
├── app
│   ├── main                 # project sub-app general structure
│   │   ├── templates
│   │   │   └── main
│   │   │       └── index.html
│   │   ├── forms.py
│   │   └── views.py
│   │
│   │
│   ├── ...                  # other sub-apps
│   │
│   │
│   ├── models               # models folder
│   │   └── models.py
│   ├── static                
│   │   ├── css
│   │   │   └── styles.css
│   │   ├── js
│   │   │   └── main.js
│   │   └── img
│   │       └── ...
│   ├── templates           # main templates folder
│   │   └── base.html
│   ├── __init__.py
│   ├── config.py
│   └── extensions.py
├── .gitignore              # .gitignore ready template
├── config.json             # JSON file for secret keys and other stuff 
├── manager.py
└── requirements.txt
```

### How to use

1. Clone this repository
    ```
    git clone https://github.com/NickNaskida/FlaskTemplate.git
    ```

2. Create virtual environment

    To create a virtual environment in the venv folder:
    ```
    python -m venv venv
    ```
    
    To activate the virtual environment
    ```
    source venv/bin/activate
    ``` 
    To deactivate the virtual environment just type
    ```
    deactivate 
    ```
    
3. Install all requirements

    ```
    pip install -r requirements.txt
    ```

4. set env variable
    Just type:
    ```
   $env:FLASK_APP="manager:app" 
    ```

5. run the project
   Just type:
    ```
   flask run
    ```