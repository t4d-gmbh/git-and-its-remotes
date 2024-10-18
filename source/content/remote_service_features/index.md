# Remote Services

{% if page %}
As we discussed in Part 1, <i class="fab fa-git"></i> is a distributed version control system (VCS) that manages and tracks change in codebases located locally (i.e. on your machine).
<i class="fab fa-git"></i> is not to be confused with <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab**, or similar, which, in turn, are remote hosting web-based platforms that use <i class="fab fa-git"></i> to offer services to store and collaborate on code remotely.

Remote services like **GitHub** or **GitLab** offer a range of features that extend beyond basic <i class="fab fa-git"></i> functionalities, making project management, collaborations and automation that much easier.
In this section, we will go over some of the key features of <i class="fab fa-git"></i>-based remote services and tools that are particularly useful for project management.
{% else %}
:::{card} <i class="fab fa-git"></i> <strong>≠</strong> remote hosting services, like <i class="fab fa-github"></i> **GitHub** or <i class="fab fa-gitlab"></i> **GitLab**

> <i class="fab fa-git"></i> = version control system (VCS) to manage and track coding changes

> <i class="fab fa-git"></i>-based remote services (e.g. **GitHub**, **GitLab**) = web-based platforms that offer services to store and facilitate collaborative coding projects, using the underlying version control tools offered by <i class="fab fa-git"></i>.
{% endif %}
:::

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./issues
./merge_pull_requests
./project_mgmt_tools
./activity_tracking
./git_features

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./issues.md
```
```{include} ./merge_pull_requests.md
```
```{include} ./project_mgmt_tools.md
```
```{include} ./activity_tracking.md
```
```{include} ./git_features.md
```
{% endif %}
