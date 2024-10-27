#### {octicon}`issue-opened;0.8em` Issues

(or _**![issue](./icons/issue.svg) Issues**_ for <i class="fab fa-gitlab"></i>)

```{epigraph}
Issues document and track tasks, bugs, thoughts, questions, and any kind of work that needs to be addressed in a repository.
```
{% if page %}
An issue allows to document all planned changes, discovered bugs, questions related to the repository, etc.
It is a genuine piece of information tied to a repository and useful in project management, especially in collaborative projects involving multiple developers or an entire community.

Different types of issues:
- Bug
- Feature requests
- Tasks
- Documentation

Generally, issues tend to have the following properties:
{% endif %}

:::{admonition} Not all {octicon}`issue-opened`/![issue](./icons/issue.svg) Issues are actually issues
:class: note, margin

Generally, any problem, question, or proposition that needs to be addressed can be documented in an issue.
:::

| Property     | Description                                                                                                                                                     |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Description** | {% if slide %}**Title** and a short **description** that outlines what needs to be addressed.{% else %}Each issue has a title and a description section that outlines the problem (expected and actual behavior), task (e.g., steps to reproduce), or an enhancement (e.g., a new feature, potential ideas or solutions to fix a bug).{% endif %} |
| **Assignees**   | {% if slide %}A designated person who is **responsible for managing** this issue.{% else %}Issues can be assigned to specific team members to clarify tasks and responsibilities and facilitate project management.{% endif %} |
| **State**       | {% if slide %}Either {octicon}`issue-opened` **opened** or {octicon}`issue-closed` **closed**{% else %}To track progress on an issue, generally they can have two states {octicon}`issue-opened` “open” (still to be resolved) and {octicon}`issue-closed` “closed” (issue has been resolved).{% endif %} |
| **Labels**      | {% if slide %}A set of arbitrary labels{% else %}Issues can be categorized using labels, e.g., “bug”, “documentation”, etc., to help organize and prioritize work.{% endif %}                                             |
| **News Feed**    | {% if slide %}A **chat-like activity feed** to comment on the issue at hand{% else %}Issues provide an activity or news feed, that displays any related changes (e.g. commits) and that anyone with can access and write comments to offer insights, feedback, and exchange ideas on how to resolve an issue.{% endif %}                             |
| **Milestone**  | {% if slide %}Affiliation to a {octicon}`milestone;0.8em` Milestone{% else %}Issues can be grouped under Milestones and be integrated into an overarching planning, even between repositories for some remote services.{% endif %}   |
