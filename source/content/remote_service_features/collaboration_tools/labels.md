#### {octicon}`tag;0.8em` Labels
&nbsp;
:::{epigraph}
Allow to categorize and organize Issues and Merge/Pull Requests in a repository, helping developers to prioritize and track work more effectively.
:::

{% if page %}
Labels are a great help for prioritizing, categorizing and navigate through Issues and Merge/Pull Requests.
On some remote service providers, Labels can be reused between repositories leading to a consistent labeling between repositories.

One thing that should be noted, is that {octicon}`tag;0.8em` Labels do not exist in <i class="fab fa-git"></i> and so they have absolutely nothing in common with {octicon}`tag;0.8em` Tags in <i class="fab fa-git"></i>.
{% else %}
<i class="fab fa-github"></i> {octicon}`tag;0.8em` Labels <i class="fa-solid fa-not-equal"></i> <i class="fab fa-git"></i> {octicon}`tag;0.8em` Tags!
{% endif %}

:::{admonition} Create scoped Labels
:class: tip, margin

Joining a property and state with `::` into a single label, like {bdg-secondary}`priority::medium`
:::

| Property                 | Description                                                                                                                                                     |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | {% if slide %}Single word or combination of words{% else %}A clear and concise name for the label that describes its purpose (e.g., "bug", "enhancement", "documentation").{% endif %}                                              |
| **Color**                | A color associated with the label{% if page %}, used for visual identification and organization within the project.{% endif %}                                                        |
| **Description**          | Optional detailed explanation of what the label represents{% if page %}, providing context for when to use it.{% endif %}                                          |
