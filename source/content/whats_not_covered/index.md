# Further Topics Not Covered

{% if page %}
There is a plethora of features, possibilities and topics that are offered by git hosting services and git itself which would be impossible to cover in a single guide. 
The scope of this guide is to provide you with the basic knowledge to get started with git and its remotes.
Nevertheless, we think there a few topics that are worth mentioning and that you might want to explore further:
{% else %}
Some additional topics we think are worth exploring:
{% endif %}

{% if page %}::::{tabs}{% else %}::::{grid}{% endif %}
{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif%} Pages
Host websites directly from your GitHub repository. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
It's a great way to showcase your projects, documentation, or any static content. For more information, see the [GitHub Pages Documentation](https://docs.github.com/en/pages).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Wiki
Share detailed information about your project. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
Every GitHub repository comes with a wiki. It's a great place to document your project's features, usage, and development process. For more information, see the [GitHub Wiki Documentation](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Releases
Manage and package software releases.
{% if page %}
```{admonition} Details
:class: tip, dropdown
They allow you to create release notes and attach binary files to a specific version of your project. For more information, see the [GitHub Releases Documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Discussions
A space for chats, Q&A, etc.
{% if page %}
```{admonition} Details
:class: tip, dropdown
It's a great way to engage with your users and contributors. For more information, see the [GitHub Discussions Documentation](https://docs.github.com/en/discussions).
```
{% endif %}
:::
{% if slide %}
::::
::::{grid}
{% endif %}

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Packages
Integrated package hosting service.
{% if page %}
```{admonition} Details
:class: tip, dropdown
It allows you to host and manage packages and dependencies alongside your source code. For more information, see the [GitHub Packages Documentation](https://docs.github.com/en/packages).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Registry
Integrated container registry.
{% if page %}
```{admonition} Details
:class: tip, dropdown
Similar to Docker Hub but integrated with GitHub and GitHub Actions.
For more information, see the [GitHub Container Registry Documentation](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} GitHub Projects
Extensive set of project management tools.
{% if page %}
```{admonition} Details
:class: tip, dropdown
GitHub Projects {octicon}`project` provide kanban-style boards, roadmaps, and tables to help you plan and track your work. You can link issues and pull requests to organize tasks and visualize progress. For more information, see the [GitHub Projects Documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} AI assistance
AI-powered coding assistance.
{% if page %}
```{admonition} Details
:class: tip, dropdown
GitHub Copilot {octicon}`copilot` provides AI-powered code completion, chat assistance, and code generation directly in your IDE and on GitHub.com. GitLab Duo offers similar AI capabilities including code suggestions, vulnerability explanations, and merge request summaries. These tools can significantly boost productivity by helping with code writing, debugging, and documentation. For more information, see the [GitHub Copilot Documentation](https://docs.github.com/en/copilot) and [GitLab Duo Documentation](https://docs.gitlab.com/ee/user/ai_features.html).
```
{% endif %}
:::
{% if slide %}
::::
::::{grid}
{% endif %}

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Paid features
Advanced security, management, enterprise support, etc.
{% if page %}
```{admonition} Details
:class: tip, dropdown
These features provide additional tools and services to help you manage and secure your projects. For more information, see the [GitHub Pricing Documentation](https://github.com/pricing).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Enterprise Plan features
Self-hosted GitHub. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
It includes all the features of GitHub.com, plus additional enterprise features. For more information, see the [GitHub Enterprise Documentation](https://docs.github.com/en/enterprise-server).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Self-hosted runners
Run sensitive workflows.
{% if page %}
```{admonition} Details
:class: tip, dropdown
Self-hosted runners give you more control over the environment in which your workflows run. For more information, see the [GitHub Actions Documentation](https://docs.github.com/en/actions).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{grid-item-card}{% endif %} Confidential data handling
Secret scanning, extra encryption, etc.
{% if page %}
```{admonition} Details
:class: tip, dropdown
GitHub provides various features to help you manage and protect confidential data.
This depends on if you're working on an Enterprise or a public repository. For more information, see the [GitHub Security Documentation](https://docs.github.com/en/code-security).
```
{% endif %}
:::

::::
