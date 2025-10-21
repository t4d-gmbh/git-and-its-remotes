{% if build == "slides" %}
## Overview: **GitHub** <i class="fab fa-github"></i> & **GitLab** <i class="fab fa-gitlab"></i>
{% endif %}

{% if build == "pages" %}
<span style="font-size:18px;">Remote services are platforms that host Git repositories on servers accessible over the internet. 
These services provide additional features that enhance collaboration, project management, and continuous integration/continuous deployment (CI/CD). 
They allow multiple users to work on the same project simultaneously, track changes, and manage versions efficiently.</span>


| **Remote Service** | **Founded** | **Acquired/Owned by** | **Popularity** | **Key Features** | **Costs** |
|--------------------|-------------|-----------------------|----------------|------------------|-----------|
| **GitHub** <i class="fab fa-github" style="font-size:50px;"></i>   | 2008        | Microsoft (2018)      | Widely used by open-source communities and enterprises.<br>Known for its user-friendly interface and extensive community support. | - **Repository hosting**<br>- **Pull requests**<br>- **Issues and bug tracking**<br>- **Wikis**<br>- GitHub Actions for CI/CD<br>- Project boards | Free for public repositories, paid plans for private repositories and additional features. |
| **GitLab** <i class="fab fa-gitlab" style="font-size:50px;"></i> | 2011        | -                     | Popular among developers and enterprises.<br>Known for its open-source nature and flexibility. | - **Repository hosting**<br>- **Merge requests**<br>- **Issues and bug tracking**<br>- **Wikis**<br>- **Integrated CI/CD**<br>- Web IDE<br>- Workspaces | Free tier, paid plans for additional features and support. |

  {% else %}

| **Aspect** | **GitHub** <i class="fab fa-github"></i> | **GitLab** <i class="fab fa-gitlab"></i> |
|------------|------------|------------|
| <span style="font-size:14px;">**Repository Hosting**</span>  | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Pull Requests/Merge Requests**</span> | <span style="font-size:14px;">Pull Requests</span> | <span style="font-size:14px;">Merge Requests</span> |
| <span style="font-size:14px;">**Issues and Bug Tracking**</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Wikis**</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**CI/CD**</span> | <span style="font-size:14px;">GitHub Actions</span> | <span style="font-size:14px;">Integrated CI/CD</span> |
| <span style="font-size:14px;">**Web IDE**</span> | <span style="font-size:14px;">github.dev and GitHub Codespaces</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Workspaces**</span> | <span style="font-size:14px;">Codespaces</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Integrations**</span> | <span style="font-size:14px;">Marketplace</span> | <span style="font-size:14px;">-</span> |

{% endif %}
