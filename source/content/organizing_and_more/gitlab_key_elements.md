### Key Elements

{% if page %}::::{tabs}{% endif %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} <i class="fas fa-user"></i> Users
Individual accounts that can own Projects and roles in other Projects or (Sub-)Groups.
{% if page %}
```{admonition} Details
:class: tip, dropdown
- Individual accounts that can access and contribute to repositories.
- Can be assigned different [roles & permissions](https://docs.gitlab.com/ee/user/permissions.html) within (Sub-)Groups and Projects.
```
{% endif %}
:::
{% if page %}:::{tab}{% else %}:::{card}{% endif%} <i class="fas fa-people-group"></i> Groups
Collection of Users and Subgroups that can own Projects and [roles & permissions](https://docs.gitlab.com/ee/user/permissions.html) in other Projects or (Sub-)Groups.
{% if page %}
```{admonition} Details
:class: tip, dropdown
- Can own Projects and be assigned different [roles & permissions](https://docs.gitlab.com/ee/user/permissions.html) within other (Sub-)Groups and Projects.
- Contain a collection of Users (i.e. Members) with individual roles (i.e. access rights)
- Can own Subgroups
- Allow for centralized management of permissions and settings.
- Provide management tools, like milestones and Kanban boarads to manage all Issues and Merge Requests of related Projects.
```
{% endif %}
:::
{% if page %}:::{tab}{% else %}:::{card}{% endif%} <i class="fas fa-people-roof"></i> Subgroups
A Group that is owned by a parent Group inheriting its members.
{% if page %}
```{admonition} Details
:class: tip, dropdown
- Nested groups within a parent (Sub-)Group.
- Inherit Users along with their roles from all parent (Sub-)Groups.
- Share all other features of Groups
```
{% endif %}
:::
{% if page %}:::{tab}{% else %}:::{card}{% endif%} <i class="far fa-folder-open"></i> Projects
Represent the actual <i class="fab fa-git"></i> repositories with an owner, as well as, [roles & permissions](https://docs.gitlab.com/ee/user/permissions.html) for other Users and (Sub-)Groups.
{% if page %}
```{admonition} Details
:class: tip, dropdown
- Projects are the core units of storage for <i class="fab fa-git"></i> repositories.
- Each project is owned either by a User, a Group or a Subgroup.
- Projects can contain their own Issues, Merge Requests, and project settings.
- Repositories can be public or private, depending on the desired visibility.
```
{% endif %}
:::
{% if page %}::::{% endif %}

