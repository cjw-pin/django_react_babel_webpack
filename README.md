# django_react_babel_webpack
A template for future reference. 

Initial structure:
├── db.sqlite3
├── manage.py
├── static
│   ├── css
│   │   └── main.css
│   ├── js
│   ├── package.json
│   ├── src
│   │   └── index.js
│   └── webpack.config.js
├── templates
│   └── index.html
└── app
    ├── __init__.py
    ├── __pycache__
    ├── settings.py
    ├── urls.py
    ├── views.py
    └── wsgi.py


Terminal Command:
npm install -D @babel/core @babel/preset-env @babel/preset-react babel-loader css-loader node-sass webpack webpack-cli 
npm install react react-dom
npm run webpack

After:
├── db.sqlite3
├── manage.py
├── static
│   ├── css
│   │   └── main.css
│   ├── dist
│   │   ├── app.bundle.js
│   │   └── app.bundle.js.map
│   ├── js
│   ├── node_modules
│   ├── package.json
│   ├── package-lock.json
│   ├── src
│   │   └── index.js
│   └── webpack.config.js
├── templates
│   └── index.html
└── twler
    ├── __init__.py
    ├── __pycache__
    ├── settings.py
    ├── urls.py
    ├── views.py
    └── wsgi.py
    
(On another terminal) Command 
python manage.py runserver
