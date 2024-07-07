# Description
This repository is a practicing of some courses and projects.  
Theses projects come from `@Codecademy` courses.

# Projects list
### Flask framework (`Python`, `Flask`, `HTML`, `Jinja`)
Concepts learned in each project :
* [01_adopt-pet](./Flask-framework/01_adopt-pet) - ([Codecademy course](https://www.codecademy.com/paths/build-python-web-apps-flask/tracks/introduction-to-flask/modules/introduction-to-flask/lessons/flask-build-your-first-app/exercises/review) / [Codecademy project](https://www.codecademy.com/paths/build-python-web-apps-flask/tracks/introduction-to-flask/modules/introduction-to-flask/projects/adopt-a-pet) ) 
    * `Flask` - import and run
    * `Flask` - static routes (URL) -> `@app.route('/static/route')`
    * `Flask` - dynamic routes (URL)  -> `/static/<var_1>/<int:var_2>')`
* [02_cooking-by-myself](./Flask-framework/02_cooking-by-myself) - ([Codecademy course](https://www.codecademy.com/paths/build-python-web-apps-flask/tracks/introduction-to-flask/modules/flask-templates-and-forms/lessons/flask-templates/exercises/review))
    * `Flask` - displaying of `Jinja` templates -> `render_template()`
    * `Flask` & `Jinja` - templates variable -> `{{ var }}`
    * `Jinja` - variable filters -> `<h1>{{ var_1 | title }}</h1>`
    * `Jinja` - "if" statements -> `{% if condition %}` / `{% else %}` / `{% endif %}`
    * `Jinja` - "for" loops -> `{% for var_1, var_2 in table.items() %}` / `{% endfor %}`
    * `Jinja` - inheritence -> `{% extends "*.html" %}` / `{% block content %}` / `{% endblock %}`
* [03_cooking-by-myself_2](./Flask-framework/03_cooking-by-myself_2) - ([Codecademy course](https://www.codecademy.com/paths/build-python-web-apps-flask/tracks/introduction-to-flask/modules/flask-templates-and-forms/lessons/flask-forms/exercises/review))
    * `Flask` - `HTTP` request allowing -> `@app.route("/", methods=["GET", "POST"])`
    * `Flask` - route selection -> `url_for('route')` / `{{ url_for('route') }}`
    * `Flask` - form creation with `FlaskForm` class -> `class MyForm(FlaskForm)`
    * `Jinja` - use of `FlaskForm` -> `{{ my_Form.my_field() }}`
    * `Flask` - data acquisition from the `FlaskForm` -> `my_Form.my_field.data`
    * `Flask` - form validation -> `validators=[DataRequired()]` / `my_form.validate_on_submit()`
    * `Flask` - route redirection -> `redirect(url_for("new_route", _external=True, _scheme='https'))`
* [04_tourist-attraction](./Flask-framework/04_tourist-attraction/) - ([Codecademy project](https://www.codecademy.com/paths/build-python-web-apps-flask/tracks/introduction-to-flask/modules/flask-templates-and-forms/projects/tourist-attractions-app))