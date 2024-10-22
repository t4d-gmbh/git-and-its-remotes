## <i class="fab fa-gitlab"></i> **GitLab**'s Organization Structure
{% if page %}**GitLab** implements a nesting approach when it comes to access rights and structuring multiple projects and related users.
In doing so relates on only two building blocks, Users and (Sub-)Groups, for managing access rights.{% endif %}
&nbsp;
```{epigraph}
In **GitLab** nested usergroups are used to manage access rights to <i class="fab fa-git"></i> repositories.
```
{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./gitlab_key_elements
./gitlab_acad_setup

```
{% else %}
<!-- BUILDING THE PAGES -->
<!-- build the page content here -->
```{include} ./gitlab_key_elements.md
```
```{include} ./gitlab_acad_setup.md
```

### 5. Project Management Features
- **Milestones**: Track progress on specific goals across multiple repositories.
- **Epics**: Group related issues and milestones for larger initiatives.
- **Issue Boards**: Visualize and manage tasks within groups and sub-groups.

## Overview
- GitLab allows for granular access control through **sub-groups**.
- Sub-groups help organize projects and manage permissions effectively.

## Access Rights Management
- **Groups and Sub-Groups**:
  - Create a **main group** for your organization.
  - Add **sub-groups** for different teams or projects.
  - Assign specific permissions to each sub-group.

- **Permission Levels**:
  - **Guest**: Limited access to view issues and merge requests.
  - **Reporter**: Can view and create issues, but cannot push code.
  - **Developer**: Can push code, manage issues, and merge requests.
  - **Maintainer**: Full access to manage the repository and settings.
  - **Owner**: Complete control over the group and its sub-groups.

### Inheritance of Access Rights
- **Inherited Permissions**:
  - Sub-groups inherit access rights from their parent group.
  - Users granted access at the parent group level automatically receive the same level of access in all sub-groups.
  - **Important**: Inherited access rights **cannot be revoked** at the sub-group level.
  - However, additional rights can be granted to users within the sub-group.

## Milestones and Kanban Boards
- **Sub-Groups Ownership**:
  - Each sub-group can have its own **milestones** to track progress on specific goals.
  - Milestones can be associated with issues and merge requests within the sub-group.

- **Kanban Boards**:
  - Sub-groups can create **issue boards** to visualize and manage tasks.
  - Boards can be customized to reflect the workflow of the sub-group.
  - Use labels and milestones to organize tasks effectively.

## Benefits
- Enhanced organization of projects within a larger group.
- Clear ownership of milestones and tasks.
- Improved collaboration and visibility across teams.

---

*Leverage GitLab's sub-groups to streamline project management and access control!*

{% endif %}
