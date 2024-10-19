### {octicon}`git-pull-request;0.8em` Merge/Pull Requests
&nbsp;
```{epigraph}
Merge Request (<i class="fab fa-gitlab"></i>) or Pull Request (<i class="fab fa-github"></i>) are formal request by a developer to have their code changes merged from one branch into another branch
```
:::{admonition} {octicon}`issue-opened;0.8em` {octicon}`arrow-right` {octicon}`git-pull-request;0.8em` 
:class: note, margin
{octicon}`git-pull-request;0.8em` Merge/Pull Requests typically relate to one or serveral {octicon}`issue-opened;0.8em` Issues.
:::
{% if page %}
In contrast to Issues that focus on documenting any kind of task that needs to be addressed, Merge/Pull requests are designed to document actual changes in a repository.
However, this leads to a rather obvious relation between Issues and Merge/Pull Requests:
{% endif %}


:::{admonition} {octicon}`git-pull-request-draft` Drafts are a thing!
:class: tip, margin

Many remote services know the concept of a _draft_ Merge/Pull request.
With a _draft_ Merge/Pull Request you might create the request even much before the implementation is completed.
:::
| Property                 | Description                                                                                                                                                     |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Source Branch**        | {% if slide %}{octicon}`git-branch` Branch containing changes{% else %}The branch containing the new changes that will be merged into the target branch (e.g., main or develop).{% endif %}                                                     |
| **Target Branch**        | {% if slide %}{octicon}`git-branch` Branch into which changes should be introduced{% else %}The branch where the changes are merged into, typically the main or develop branch.{% endif %}                                                                          |
| **Description** | {% if slide %}**Title** and a short **description** that outlines what is implemented and how.{% else %}Each Merge/Pull Request has a title and a brief description outlining the changes made in the branch. It can also contain specific keywords ([<i class="fab fa-github"></i>](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/using-keywords-in-issues-and-pull-requests) or [<i class="fab fa-gitlab"></i>](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)), such as the introduction to close a specific issue once the request is accepted.{% endif %} |
| **Assignees**   | {% if slide %}A designated **responsible for the implementation** of the changes.{% else %}Merge/Pull Request can be assigned to specific team members to clarify responsibilities and facilitate project management.{% endif %}                                      |
| **Reviewers**            | {% if slide %}Person(s) responsible for overseeing the introduction of changes{% else %}One or several members of the repository assigned to review the changes and provide feedback. Typically, a reviewer should be very familiar with the parts of the target branch that are affected by the changes.{% endif %}                                                                                             |
| **State**       | {% if slide %}Either {octicon}`git-pull-request` **opened**, {octicon}`git-merge` **merged** or {octicon}`git-pull-request-closed` **closed**{% else %}To track progress on an Merge/Pull Request, generally it can have three states {octicon}`git-pull-request` “open” (still to be merged), {octicon}`git-merge` **merged** (the request has been accepted and the source branch was merged into the target branch) an {octicon}`git-pull-request-closed` “closed” (the request was denied).{% endif %} |
| **Labels**      | {% if slide %}A set of arbitrary labels{% else %}Issues can be categorized using labels, e.g., “bug”, “documentation”, etc., to help organize and prioritize work.{% endif %}                                             |
| **News Feed**    | {% if slide %}A **chat like activity feed** that allows commenting{% else %}Issues provide an activity or news feed, that displays any related changes and that anyone with can access and write comments to offer insights, feedback, and exchange ideas on how to resolve an issue.{% endif %}                             |
| **Milestone**  | {% if slide %}Affiliation to a {octicon}`milestone;0.8em` Milestone{% else %}Identical to issues, Merge/Pull Requests can be grouped under milestones and be integrated into an overarching planning, even between repositories for some remote services.{% endif %}   |



{% if page %}
In a collaborative project, it is a useful tool for:
- Review code changes before merging
- Discuss changes and suggest improvements
- Testing code to ensure changes don’t break the project or the overall workflow.
- Approve code changes or workflow (by one or several developers).



Pull / Merge Request workflow:
1. Create branch
2. Commit changes (any work done on the branch)
3. Push branch into remote repository
4. Create Pull / Merge Request to propose the changes from the source to the target branch
5. Review and Feedback, requesting additional changes as needed
(6. Automated Testing run to ensure the changes don’t introduce bugs or other problems)
7. Approval
8. Merge changes into target branch

{% endif %}

