# Project Management
{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./workflow
./milestones

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./workflow.md
```
```{include} ./milestones.md
```
{% endif %}
