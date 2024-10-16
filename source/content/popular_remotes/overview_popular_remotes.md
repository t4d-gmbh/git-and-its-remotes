{% if build == "slides" %}
## Remote Services Overview
{% endif %}

<span style="font-size:14px;">Remote services are platforms that host Git repositories on servers accessible over the internet. These services provide additional features that enhance collaboration, project management, and continuous integration/continuous deployment (CI/CD). They allow multiple users to work on the same project simultaneously, track changes, and manage versions efficiently.</span>

{% if build == "pages" %}

| **Remote Service** | **Founded** | **Acquired/Owned by** | **Popularity** | **Key Features** | **Costs** |
|--------------------|-------------|-----------------------|----------------|------------------|-----------|
| **GitHub** ![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)   | 2008        | Microsoft (2018)      | Widely used by open-source communities and enterprises.<br>Known for its user-friendly interface and extensive community support. | - **Repository hosting**<br>- **Pull requests**<br>- **Issues and bug tracking**<br>- **Wikis**<br>- GitHub Actions for CI/CD<br>- Project boards | Free for public repositories, paid plans for private repositories and additional features. |
| **GitLab** ![GitLab Logo](https://about.gitlab.com/images/press/logo/png/gitlab-icon-rgb.png) | 2011        | -                     | Popular among developers and enterprises.<br>Known for its open-source nature and flexibility. | - **Repository hosting**<br>- **Merge requests**<br>- **Issues and bug tracking**<br>- **Wikis**<br>- **Integrated CI/CD**<br>- Web IDE<br>- Workspaces | Free tier, paid plans for additional features and support. |
| **Bitbucket** ![Bitbucket Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Atlassian_Bitbucket_Logo.png/800px-Atlassian_Bitbucket_Logo.png) | 2008        | Atlassian             | Popular among enterprises and small teams.<br>Known for its integration with other Atlassian products (Jira, Confluence). | - **Repository hosting** (supports both Git and Mercurial)<br>- **Pull requests**<br>- **Issues and bug tracking**<br>- Bitbucket Pipelines for CI/CD<br>- Integrations with Jira and Confluence (project management tools) | Free for small teams, paid plans for larger teams and additional features. |
  
  {% else %}

| **Aspect** | **GitHub** | **GitLab** |**Bitbucket** |
|------------|------------|------------|--------------|
| <span style="font-size:14px;">**Repository Hosting**</span>  | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span>                                                |
| <span style="font-size:14px;">**Pull Requests/Merge Requests**</span> | <span style="font-size:14px;">Pull Requests</span> | <span style="font-size:14px;">Merge Requests</span> | <span style="font-size:14px;">Pull Requests</span> |
| <span style="font-size:14px;">**Issues and Bug Tracking**</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Wikis**</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**CI/CD**</span> | <span style="font-size:14px;">GitHub Actions</span> | <span style="font-size:14px;">Integrated CI/CD</span> | <span style="font-size:14px;">Bitbucket Pipelines</span> |
| <span style="font-size:14px;">**Web IDE**</span> | <span style="font-size:14px;">github.dev and GitHub Codespaces</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Cloud IDE</span> |
| <span style="font-size:14px;">**Workspaces**</span> | <span style="font-size:14px;">Codespaces</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Integrations**</span> | <span style="font-size:14px;">Marketplace</span> | <span style="font-size:14px;">-</span> | <span style="font-size:14px;">Integrations with Jira and Confluence</span> |

{% endif %}