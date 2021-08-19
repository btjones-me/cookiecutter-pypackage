{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
# {{ cookiecutter.project_name }}
{% if is_open_source %}
![Python Package](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_repo }}/workflows/Python%20package/badge.svg)
{%- endif %}

{{ cookiecutter.project_short_description }}

{% if is_open_source %}
* Free software: {{ cookiecutter.open_source_license }}
{% endif %}

# Features

* TODO

# Credits

This package was created with Cookiecutter and the `btjones-me/cookiecutter-pypackage` project template.

* Cookiecutter: https://github.com/cookiecutter/cookiecutter
* btjones-me/cookiecutter-pypackage: https://github.com/btjones-me/cookiecutter-pypackage
