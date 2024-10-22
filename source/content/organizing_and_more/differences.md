## Differences Between GitHub and GitLab

:::{admonition} <i class="far fa-folder-open"></i> Project {math}`\neq` {octicon}`project` Project
:class: warning
In <i class="fab fa-gitlab"></i> **GitLab** a <i class="fab fa-git"></i> repository is represented in a <i class="far fa-folder-open"></i> Project while on <i class="fab fa-github"></i> **GitHub** it is a {octicon}`repo` Repository.

What is refered to as {octicon}`project` Project in <i class="fab fa-github"></i> **GitHub** shares more similarities with a <i class="fas fa-people-roof"></i> Subgroup in <i class="fab fa-gitlab"></i> **GitLab**.
:::

### Access Rights and Sub-Groups

| Feature                     | GitHub                                      | GitLab                                      |
|-----------------------------|---------------------------------------------|---------------------------------------------|
| **Access Control**          | Managed through Teams and Repository settings | Managed through Subgroups and Repository settings  |
| **Permission Levels**       | Read, Triage, Write, Maintain, Admin       | Guest, Reporter, Developer, Maintainer, Owner |
| **Inheritance**             | Permissions can be inherited from organization-level settings | Subgroups inherit permissions from parent (Sub-)Groups, but cannot revoke them |
| **Additional Rights**       | Can assign different permissions to Teams   | Can grant additional rights in Subgroups   |
