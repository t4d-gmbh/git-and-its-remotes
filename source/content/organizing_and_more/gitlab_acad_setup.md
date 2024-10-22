### GitLab's Organization Structure in Action

**GitLab**'s approach to manage access control requires some care in order to create a organisational setup that facilitates collaboration and project management.
The key aspect to take into account is the inheritance of Members (i.e. Users) along with their roles (i.e. access right).

For the exemplary case of a research group we suggest the following setup:

1. **Create a Group**
  - Decide on the transparency level within the group by [identifying a default role](https://docs.gitlab.com/ee/user/permissions.html#analytics) for members of the Group.
  - Invite all permanent group members.
  - Designate 1-2 Users with elevated privileged (i.e. [Maintainers](https://docs.gitlab.com/ee/user/permissions.html#analytics))
