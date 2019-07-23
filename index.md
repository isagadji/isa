# Hello index.md

#### GitHub repos.
{% for repository in site.github.public_repositories %}
* [{{ repository.full_name }}]({{ repository.html_url }})
{% endfor %}

{{ dump(site.github.public_repositories) }}