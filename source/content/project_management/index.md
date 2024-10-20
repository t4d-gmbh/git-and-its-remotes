# Project Management
&nbsp;
```{epigraph}
The process of planning, executing and closing a project within a defined timeline and budged.
```
In this course we will focus on transcribing this very general definition into the context of <i class="fab fa-git"></i> and its remote services, more precisedly <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab**.

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./workflow
./milestones
./feature_branch_reload/index

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./workflow.md
```
```{include} ./milestones.md
```
```{include} ./feature_branch_reload/index.md
```
```{include} ./feature_branch_reload/workflow.md
```
{% endif %}
