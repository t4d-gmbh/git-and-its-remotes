{% if build == "slides" %}
## Overview: **GitHub** <i class="fab fa-github"></i> & **GitLab** <i class="fab fa-gitlab"></i>
{% endif %}

{% if build == "pages" %}
<span style="font-size:18px;">Remote services are platforms that host Git repositories on servers accessible over the internet. 
These services provide additional features that enhance collaboration, project management, and continuous integration/continuous deployment (CI/CD). 
They allow multiple users to work on the same project simultaneously, track changes, and manage versions efficiently.</span>


| **Remote service** | **GitHub** <i class="fab fa-github" style="font-size:50px;"></i> | **GitLab** <i class="fab fa-gitlab" style="font-size:50px;"></i> |
|--------------------|------------|------------|
| **Founded** | 2008 | 2011 |
| **Acquired/Owned by** | Microsoft (2018) | - |
| **Popularity** | Widely used by open-source communities and enterprises.<br>Known for its user-friendly interface and extensive community support. | Popular among developers and enterprises.<br>Known for its open-source nature and flexibility. |
| **Platform features** | - Repository hosting<br>- Pull requests<br>- Issues and bug tracking<br>- Wikis<br>- GitHub Actions for CI/CD<br>- Project boards<br>- AI assistance: [GitHub Copilot](https://docs.github.com/en/copilot/get-started/what-is-github-copilot)<br>- Command-line client: [GitHub CLI (`gh`)](https://cli.github.com/manual/) | - Repository hosting<br>- Merge requests<br>- Issues and bug tracking<br>- Wikis<br>- Integrated CI/CD<br>- Web IDE<br>- Workspaces<br>- AI assistance: [GitLab Duo](https://docs.gitlab.com/user/gitlab_duo/)<br>- Command-line client: [GitLab CLI (`glab`)](https://docs.gitlab.com/cli/) |
| **Costs** | Free for public repositories, paid plans for private repositories and additional features. | Free tier, paid plans for additional features and support. |

**AI assistance:** Availability and capabilities depend on the plan and organizational settings.

**Command-line clients:** These clients provide terminal access to platform features such as issues, pull/merge requests, and CI/CD workflows.
They complement `git`; they do not replace it.
Their scriptable commands and structured output also make them an efficient interface for AI agents, subject to the authenticated account’s permissions.

  {% else %}

| **Platform feature** | **GitHub** <i class="fab fa-github"></i> | **GitLab** <i class="fab fa-gitlab"></i> |
|------------|------------|------------|
| <span style="font-size:14px;">**Repository Hosting**</span>  | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Pull Requests/Merge Requests**</span> | <span style="font-size:14px;">Pull Requests</span> | <span style="font-size:14px;">Merge Requests</span> |
| <span style="font-size:14px;">**Issues and Bug Tracking**</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Wikis**</span> | <span style="font-size:14px;">Yes</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**CI/CD**</span> | <span style="font-size:14px;">GitHub Actions</span> | <span style="font-size:14px;">Integrated CI/CD</span> |
| <span style="font-size:14px;">**Web IDE**</span> | <span style="font-size:14px;">github.dev and GitHub Codespaces</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Workspaces**</span> | <span style="font-size:14px;">Codespaces</span> | <span style="font-size:14px;">Yes</span> |
| <span style="font-size:14px;">**Integrations**</span> | <span style="font-size:14px;">Marketplace</span> | <span style="font-size:14px;">-</span> |
| <span style="font-size:14px;">**AI assistance**</span> | <span style="font-size:14px;">GitHub Copilot</span> | <span style="font-size:14px;">GitLab Duo</span> |
| <span style="font-size:14px;">**Command-line client**</span> | <span style="font-size:14px;">GitHub CLI (`gh`)</span> | <span style="font-size:14px;">GitLab CLI (`glab`)</span> |

{% endif %}
