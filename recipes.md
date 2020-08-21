# Recipes

{% for recipe in site.recipes %}
* [{{ recipe.title }}]({{site.baseurl}}{{recipe.url}})
{% endfor %}
