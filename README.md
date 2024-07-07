# Description
This repository is a practicing of some courses and projects.  
Theses projects come from `@Codecademy` courses.

# Projects list
### Flask framework (`Python`, `Flask`, `HTML`, `Jinja`)
Concepts learned in each project :
* [adopt-pet](./Flask-framework/adopt-pet)
    * `Flask` import and run
    * `Flask` static routes (URL) -> `@app.route('/static/route')`
    * `Flask` dynamic routes (URL)  -> `/static/<var_1>/<int:var_2>')`
* [cooking-by-myself](./Flask-framework/cooking-by-myself) 
    * `Flask` function `render_template()`
    * `Flask` & `Jinja` templates variable -> `{{ var }}`
    * `Jinja` variable filters -> `<h1>{{ var_1 | title }}</h1>`
    * `Jinja` "if" statements -> `{% if condition %}` / `{% else %}` / `{% endif %}`
    * `Jinja` "for" loops -> `{% for var_1, var_2 in table.items() %}` / `{% endfor %}`
    * `Jinja` inheritence -> `{% extends "*.html" %}` / `{% block content %}` / `{% endblock %}`
