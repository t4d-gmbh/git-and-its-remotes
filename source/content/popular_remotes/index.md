# Popular Remotes

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./overview_popular_remotes
./github
./gitlab
<!-- ./bitbucket -->
./remote_services_at_uzh_imathGitLab
./remote_services_at_uzh_uzhGitLab
./remote_services_at_uzh_uzhGithub

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
<!-- ```{include} ./bitbucket.md
``` -->
# Remote Services at the University of Zurich
```{include} ./remote_services_at_uzh_imathGitLab.md
```
```{include} ./remote_services_at_uzh_uzhGitLab.md
```
```{include} ./remote_services_at_uzh_uzhGithub.md
```

{% endif %}
