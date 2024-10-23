### Setting up an Organization

{% if page %}
:::{margin} <i class="fab fa-gitlab"></i> Roles:
  - **Guest**: Limited access to view Issues and Merge Requests.
  - **Reporter**: Can view and create Issues, but cannot push code.
  - **Developer**: Can push code, manage Issues, and Merge Requests.
  - **Maintainer**: Full access to manage the Project and settings.
  - **Owner**: Complete control over the Group and its Subgroups.
:::
{% endif %}
{% if page %}
**GitLab**'s approach to manage access control requires some care in order to create a organizational setup that facilitates collaboration and project management.
The key aspect to take into account is the inheritance of Members (i.e. Users) along with their roles (i.e. access rights).
{% endif %}

For a small organization, like a research group or small company, we suggest the following approach:

{% if page %}##### {% endif %}1. **Create a <i class="fas fa-people-group"></i> Group** {% if slide %} Invite all permanent group members as "Developer" or "Reporter".
{% else %}
  - Create a new Group to represent your organization.
  - Set the [visibility level](https://docs.gitlab.com/ee/user/public_access.html).
    :::{note}
    Restrictions in the visibility are inherited, i.e. in a _private_ Group you can only have _private_ Projects.
    However, in a _public_ Group it is possible to have _private_ Projects.
    :::
  - Decide on the transparency level within the group by [identifying a default role](https://docs.gitlab.com/ee/user/permissions.html) for members of the Group.
    :::{tip}
    [Developer](https://docs.gitlab.com/ee/user/permissions.html#repository) is a good default role, as it allows to view all Projects and suggest edits without being able to change the content of a Project completely.
    :::
  - Invite all permanent group members.
  - Designate 1-2 Users with elevated privileges.
    We recommend to have more than one [Owner and some Maintainers](https://docs.gitlab.com/ee/user/permissions.html#repository).
{% endif %}

{% if page %}##### {% endif %}2. **Create <i class="fas fa-people-roof"></i> Subgroups** {% if slide %} With designated Owners for distinct research areas, projects, labs, etc.
{% else %}
  - Fill in the short description to clarify what this Subgroup is about.
  - Designate 1-2 Users with elevated privileged (i.e. designate another Owner and maybe some Maintainers)
    :::{tip}
    You can invite Users that are already part of any parent (Sub-)Group again and "escalate" their role in this Subgroup.
    In doing so you can designate Owners or Maintainers of only Subgroups.

    ```{note}
    The inverse is not possible: You can only give a User **more rights** than what was already inherited from the parent (Sub-)Group.
    ```
    :::
{% endif %}

{% if page %}##### {% endif %}3. **Invite additional <i class="fas fa-user"></i> Users** {% if slide %} Add ext. collaborators and temp. members directly to Subgroups
{% else %}
  - Add external collaborators and short-term members of your group directly into the corresponding Subgroups.
    :::{tip}
    It is also possible to add entire (Sub-)Groups which can be a great setup for a collaborative project between two or more research groups.
    :::
{% endif %}

{% if page %}##### {% endif %}4. **Gradually <i class="fas fa-universal-access"></i> escalate Privileges**{% if slide %} Members of Subgroups should be able to take advantage of **GitLab**'s features
{% else %}
  - Elevate the privileges of <i class="fas fa-user"></i> Users in Subgroups to make sure that the members of a Subgroup can take advantage of **GitLab**'s remote features to the fullest extent.
  - Think of re-inviting members of parent (Sub-)Groups to elevate their roles.
{% endif %}
