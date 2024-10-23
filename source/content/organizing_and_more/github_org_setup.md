### Setting up a GitHub Organization {octicon}`organization`

{% if page %}
:::{margin} <i class="fab fa-github"></i> Roles in Organizations:
  - **Read**: Can view repositories and issues.
  - **Triage**: Can manage issues and pull requests.
  - **Write**: Can push code, manage issues, and pull requests.
  - **Maintain**: Full access to manage non-destructive, non-sensitive settings.
  - **Admin**: Complete control over the repository and its settings, incl. managing security and deleting the repository.
:::
{% endif %}

{% if page %}
In **GitHub** Organization members can have different access levels to the repositories that are owned by the Organization.
Organization owners can manage the access rights of members and create Teams to group members with similar roles or responsibilities.
They can also set base permissions for the Organization and its repositories.
Organization owners have admin access to all repositories and can manage the Organization's settings.

:::{margin} <i class="fab fa-github"></i> Enterprise Cloud:
GitHub Enterprise Cloud offers additional security features and compliance tools for organizations, i.a. SAML single sign-on, automated security updates, and advanced auditing, and Organization specific roles.
:::
{% endif %}

For a small organization, like a research group or small company, we suggest the following approach:

{% if page %}##### {% endif %}1. **Create a {octicon}`organization` Organization** {% if slide %} Invite all permanent research group members with "Write" or "Maintain" Roles.
{% else %}
  - Create a new Organization to represent your research group.
    :::{note} Assign multiple Owners to the Organization.
    If an organization only has one owner, the organization's projects can become inaccessible if the owner is unreachable.
    :::
  - Unlike in GitLab, the visibility of an Organization in GitHub is always public. However, repositories owned by the Organization can be private.
{% endif %}

{% if page %}##### {% endif %}2. **Create {octicon}`people` Teams** {% if slide %} Represent your research-groups hierarchy with Teams and Teams-of-Teams (child Teams). 
This can be useful for managing permissions and access to repositories.
{% else %}
  - Create Teams to represent different research groups, projects, or labs within the Organization.
  - Assign members to the Teams based on their roles and responsibilities.
    :::{tip}
    Assign two or more Organization members as *Team Maintainers* to help manage the Team's settings and permissions.
    :::
  - Teams can be nested within other Teams to reflect the research group's hierarchy.
{% endif %}

{% if page %}##### {% endif %}3. **Invite additional {octicon}`person` Users** {% if slide %} Add ext. collaborators and temp. members who are not part of your {octicon}`organization` Organization directly to {octicon}`repo` Repositories.
{% else %}
  - Add external collaborators who are not part of your {octicon}`organization`Organization directly to the corresponding {octicon}`repo`Repositories.
{% endif %}
