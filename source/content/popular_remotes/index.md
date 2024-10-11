# Popular Remotes

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./overview_popular_remotes
./github

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./overview_popular_remotes.md
```
# Remote Services in Detail
```{include} ./github.md
```
{% endif %}
