# Organizing Projects
{% if page %}
Remote services provide a range of management features that extend beyond individual <i class="fab fa-git"></i> repositories. These features include robust tools for project management and access control. They typically offer various methods to organize developers and other contributors into entities with defined roles and permissions within the platform.

In this section, we will explore how <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab** enable the structuring of contributor groups, highlighting how each platform's approach enhances access management and fosters collaboration.
{% else %}
Remote services like <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab**  provide management features that **organize contributors into entities with defined roles and permissions**, enhancing access management and collaboration.
{% endif %}



{% if build == "slides" %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./example_situation_academia
./github_org_elements
./gitlab_org_elements
./differences

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./example_situation_academia.md
```
```{include} ./github_org_elements.md
```
```{include} ./gitlab_org_elements.md
```
```{include} ./differences.md
```
{% endif %}
