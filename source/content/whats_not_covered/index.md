# Further Topics Not Covered

{% if page %}
There is a plethora of features, possibilities and topics that are offered by git hosting services and git itself which would be impossible to cover in a single guide. 
The scope of this guide is to provide you with the basic knowledge to get started with git and its remotes.
Nevertheless, we think there a few topics that are worth mentioning and that you might want to explore further:
{% else %}
Some additional topics we think are worth exploring:
{% endif %}

{% if page %}::::{tabs}{% endif %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} Pages
Host websites directly from your GitHub repository. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
It's a great way to showcase your projects, documentation, or any static content. For more information, see the [GitHub Pages Documentation](https://docs.github.com/en/pages).
```
{% endif %}
:::

{% if page %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} Wiki
Share detailed information about your project. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
Every GitHub repository comes with a wiki. It's a great place to document your project's features, usage, and development process. For more information, see the [GitHub Wiki Documentation](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis).
```
{% endif %}
:::
{% endif %}


{% if page %}:::{tab}{% else %}:::{card}{% endif%} Releases
Manage and package software releases.
{% if page %}
```{admonition} Details
:class: tip, dropdown
They allow you to create release notes and attach binary files to a specific version of your project. For more information, see the [GitHub Releases Documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases).
```
{% endif %}
:::

{% if page %} 
{% if page %}:::{tab}{% else %}:::{card}{% endif%} Discussions
A space for your community to have conversations, ask questions, and share ideas. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
It's a great way to engage with your users and contributors. For more information, see the [GitHub Discussions Documentation](https://docs.github.com/en/discussions).
```
{% endif %}
:::
{% endif %}

{% if page %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} Packages
Package hosting service, fully integrated with GitHub.
{% if page %}
```{admonition} Details
:class: tip, dropdown
It allows you to host and manage packages and dependencies alongside your source code. For more information, see the [GitHub Packages Documentation](https://docs.github.com/en/packages).
```
{% endif %}
:::
{% endif %}

{% if page %}:::{tab}{% else %}:::{card}{% endif%} Registry
GitHub Container Registry for hosting and managing Docker container images within your GitHub repositories. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
Similar to Docker Hub but integrated with GitHub and GitHub Actions.
For more information, see the [GitHub Container Registry Documentation](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{card}{% endif%} Paid features
Various paid features offer advanced security, team management, and enterprise support, etc.
{% if page %}
```{admonition} Details
:class: tip, dropdown
These features provide additional tools and services to help you manage and secure your projects. For more information, see the [GitHub Pricing Documentation](https://github.com/pricing).
```
{% endif %}
:::

{% if page %}:::{tab}{% else %}:::{card}{% endif%} Enterprise Plan features
Host GitHub on your own servers, providing you with full control over your GitHub environment and data. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
It includes all the features of GitHub.com, plus additional enterprise features. For more information, see the [GitHub Enterprise Documentation](https://docs.github.com/en/enterprise-server).
```
{% endif %}
:::

{% if page %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} Self-hosted runners
Run your workflows on GitHub-hosted runners or your own self-hosted runners. 
{% if page %}
```{admonition} Details
:class: tip, dropdown
Self-hosted runners give you more control over the environment in which your workflows run. For more information, see the [GitHub Actions Documentation](https://docs.github.com/en/actions).
```
{% endif %}
:::
{% endif %}

{% if page %}
{% if page %}:::{tab}{% else %}:::{card}{% endif%} Confidential data handling
Secret scanning and encrypted secrets, where to store sensitive information securely, and how to manage and protect confidential data.
{% if page %}
```{admonition} Details
:class: tip, dropdown
GitHub provides various features to help you manage and protect confidential data.
This depends on if you're working on an Enterprise or a public repository. For more information, see the [GitHub Security Documentation](https://docs.github.com/en/code-security).
```
{% endif %}
{% endif %}

{% if page %}::::{tabs}{% endif %}