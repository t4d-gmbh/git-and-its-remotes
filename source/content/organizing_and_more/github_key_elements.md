### Key Elements

{% if page %}::::{tabs}{% endif %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} {octicon}`person` Users
Individual accounts that can own Organizations, (nested-)Teams, and Repositories.
They can be assigned to different project management elements and roles like {octicon}`issue-opened` Issues, {octicon}`git-pull-request` Pull Requests, {octicon}`milestone` Milestones, {octicon}`project`Projects, etc.
{% if page %}
```{admonition} Details
:class: tip, dropdown
- Individual accounts that can access and contribute to repositories.
- Can be assigned different [roles & permissions](https://docs.github.com/en/get-started/learning-about-github/access-permissions-on-github) within Organizations, (nested-)Teams and Repositories.
```
{% endif %}
:::
{% if page %}:::{tab}{% else %}:::{card}{% endif%} {octicon}`organization` Organizations
Shared accounts for collaboration across multiple projects. 

{% if page %}
```{admonition} Details
:class: tip, dropdown
They are a collection of repositories and users. In academia, they can provide a hub for showcasing research projects, coursework, and collaborative efforts.
```
{% endif %}
:::
{% if page %}:::{tab}{% else %}:::{card}{% endif%} {octicon}`people` Teams
Teams consist of members from the organization (not external collaborators) who have access to specific repositories. To reflect a group's hierarchy, teams can be nested within other teams, with child teams inheriting the permissions of their parent teams. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
Hierarchies of Teams can be used to manage permissions and access to repositories. 
In an academic setting, teams can be created e.g. for a group of students working on a project or a research team collaborating on a paper.
```
{% endif %}
:::
{% if page %}:::{tab}{% else %}:::{card}{% endif%} {octicon}`repo` Repositories
Containers for project files, code, and documentation. {% if page %}
```{admonition} Details
:class: tip, dropdown
Repositories can be public or private and can be used to organize and manage project files. In academia, repositories can store research data, code, and manuscripts.
```
{% endif %}
:::
{% if page %}::::{% endif %}
