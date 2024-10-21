## <i class="fab fa-git"></i> + Remote Tools Interactions
&nbsp;
{% if page %}
With <i class="fab fa-git"></i> we posses a powerful tool to structure how we develop the content of a repository.
Tools like Issues and Merge/Pull Request, provided by remote services, allow us to extensively document and track activities around any sort of plans, ideas, issues (not an Issue!), questions and suggestions.
What we are still missing is to learn how events and actions in <i class="fab fa-git"></i> relate to events and actions within these remote tools, and vice-versa.

As a start, let's simply clarify that:
{% endif %}
```{epigraph}
Some remote services can trigger events and actions in <i class="fab fa-git"></i> based on events and actions within their collaboration tools, and vice-versa.
```
{% if page %}
For <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab** there are many such triggers and it is not the goal here to provide a list of them.
However, we would like to point out, that these triggers generally aim to synchronize the life-cycle of typical workflows.
For example, pushing a new branch to the remote server will trigger the suggestion to create a Merge/Pull Request. Or merging one branch into another will close any open Merge/Pull Requests that has the one branch as source branch and the other as target branch.

Even though remote services implement triggers in both directions, the underlying purpose of such triggers it clearly to position tools like Issues and Merge/Pull Requests as interfaces capable to reflect <i class="fab fa-git"></i> events and abstract some <i class="fab fa-git"></i> operations.
{% endif %}
```{epigraph}
In doing so remote services integrate typical <i class="fab fa-git"></i> workflows, like creating or merging a branch, into project management workflows performed with their collaboration tools.
```
