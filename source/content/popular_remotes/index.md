# Popular Remotes

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./overview_popular_remotes
./github
./gitlab
./bitbucket

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./overview_popular_remotes.md
```
# Remote Services in Detail
```{include} ./github.md
```
```{include} ./gitlab.md
```
```{include} ./bitbucket.md
```

{% endif %}
