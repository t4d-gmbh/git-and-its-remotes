# Organizing your projects

{% if build == "slides" %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./example_situation_accademia
./github_org_elements
./gitlab_org_elements

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./example_situation_accademia.md
```
```{include} ./github_org_elements.md
```
```{include} ./gitlab_org_elements.md
```
{% endif %}
