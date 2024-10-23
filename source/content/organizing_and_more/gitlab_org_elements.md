## <i class="fab fa-gitlab"></i> **GitLab**'s Organization Structure
{% if page %}**GitLab** implements a nesting approach when it comes to access rights and structuring multiple projects and related users.
It relies on only two building blocks, Users and (Sub-)Groups, for managing access rights.{% endif %}
&nbsp;
```{epigraph}
In **GitLab** nested usergroups are used to manage access rights to <i class="fab fa-git"></i> repositories.
```
{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./gitlab_key_elements
./gitlab_org_setup

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./gitlab_key_elements.md
```
```{include} ./gitlab_org_setup.md
```
```{include} ./gitlab_setup_usage.md
```
{% endif %}
