### GitLab's Organization Structure in Action

**GitLab**'s approach to manage access control requires some care in order to create a organisational setup that facilitates collaboration and project management.
The key aspect to take into account is the inheritance of Members (i.e. Users) along with their roles (i.e. access right).

For the exemplary case of a research group we suggest the following setup:

{% if page %}##### {% endif %}1. **Create a Group** ✨{% if slide %}
{% else %}
  - Set the [visibility level](https://docs.gitlab.com/ee/user/public_access.html)
    :::{note}
    Restrictions in the visibility are inherited, i.e. in a _private_ group you can only have _private_ Projects.
    However, in a _public_ group it is possible to have _private_ Projects.
    :::
  - Decide on the transparency level within the group by [identifying a default role](https://docs.gitlab.com/ee/user/permissions.html#analytics) for members of the Group.
  - Invite all permanent group members.
  - Designate 1-2 Users with elevated privileged (i.e. [Maintainers](https://docs.gitlab.com/ee/user/permissions.html#analytics))
{% endif %}

{% if page %}##### {% endif %}2. **Create Subgroups** ✨{% if slide %} For distinct research areas, projects, labs, etc.
{% else %}
  - Designate 1-2 Users with elevated privileged (i.e. [Maintainers](https://docs.gitlab.com/ee/user/permissions.html#analytics))
  - ...
{% endif %}

{% if page %}##### {% endif %}1. **Invite additional Users** ✨{% if slide %}
{% else %}
  - Set the [visibility level](https://docs.gitlab.com/ee/user/public_access.html)
    :::{note}
    Restrictions in the visibility are inherited, i.e. in a _private_ Group you can only have _private_ Projects.
    However, in a _public_ Group it is possible to have _private_ Projects.
    :::
  - ...
{% endif %}
