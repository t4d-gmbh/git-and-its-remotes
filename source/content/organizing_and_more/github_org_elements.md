## <i class="fab fa-github"></i> **GitHub**'s Organization Structure

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
Teams are groups of organization members (not outside collaborators) with access to specific repositories. 
To reflect a group's hierarchy, teams can be nested within other teams.
Child teams inherit the permissions of their parent team. 
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

{% if page %}

### GitHub's Organization Structure in Action

In an academic context, GitHub's organization structure can be leveraged to streamline collaboration and project management. Here's how it might look:

- {octicon}`organization` **Organization Creation**: Your university's research lab could create an organization on GitHub to host various research projects. The faculty members could be the owners of the organization, overseeing the projects and managing access.

- {octicon}`people` **Team Formation**: Create teams within the organization for different research groups or projects. Each team would have access to specific repositories based on their roles and responsibilities. This might be useful for managing permissions and collaboration within the lab. For example, a team of students working on a specific project could have access to the corresponding repository.

- {octicon}`repo` **Repository Management**: Each research project could have its own repository within the organization (or multiple repositories). These repositories could contain code, data, manuscripts, and other project-related files. By using repositories, you can maintain version control, track changes, and collaborate effectively on research projects.

- **Progress Tracking**: Track the research project's progress using {octicon}`issue-opened` issues, {octicon}`project` project boards (which can be linked to multiple repositories), and {octicon}`git-pull-request;0.8em` pull requests within the repositories. This would help in managing tasks, tracking {octicon}`milestone;0.8em` milestones, and reviewing contributions from team members.

#### Collaborating with External Partners

Invite collaborators to specific repositories or teams within the organization, enabling them to contribute to the project. This can be particularly useful when working with industry partners, other research groups, or open-source communities.

{% endif %}


