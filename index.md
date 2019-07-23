# Hello index.md


{% for repository in site.github.public_repositories %}
* [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

{{ dump(site.github.public_repositories) }}