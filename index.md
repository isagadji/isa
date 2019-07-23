# Hello index.md


{% for repository in site.github.public_repositories %}
* [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

{% debug(site.github.public_repositories) %}
{% dump(site.github.public_repositories) %}