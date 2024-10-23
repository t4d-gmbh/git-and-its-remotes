### Workflow

:::{admonition} <i class="fab fa-gitlab"></i> **GitLab**
:class: note, margin
Allows to perform steps **2** and **3** in a combined manner.
:::
{% if page %}##### {% endif %}1. **Create an Issue** 📝{% if slide %} Define and plan feature{% endif %}
{% if page %}
- **Identify the Feature**: Start by identifying the feature you want to develop.
- **Check for similar Issues**: It is always a good practice check for existing Issues; there's no need to create duplicates if an identical or similar Issue already exists.
- **Formulate the Issue**: Include details:
  - Description of the feature
  - Acceptance criteria
  - Any relevant design mockups or specifications
  - Priority and estimated effort
  - If it is a bug, include steps to reproduce and state the expected behavior
{% endif %}

{% if page %}##### {% endif %}2. **Create a Feature Branch** 🌿{% if slide %} Branch from healthy reference{% endif%}
{% if page %}
- **Branch from the healthy reference**: Create a new branch from the relevant healthy reference (e.g., `main` or `develop`).
  Name the branch descriptively, using a convention like `feature/issue-number-description` (e.g., `feature/123-add-login-functionality`).
  ::::{note}
  Remote services might offer to directly create a branch with a descriptive name that will allow linking the branch with the Issue.

  :::{card} <i class="fab fa-github"></i> **GitHub**
  Offers to create a branch or link an existing Pull Request.
  The option to create a related Pull Request is postponed to the first commit on the branch.
  :::
  :::{card} <i class="fab fa-gitlab"></i> **GitLab**
  From an opened issue it is possible to also directly create a Merge Request along withe a dedicated branch.
  When doing so, the Merge Request is created as a _draft_.
  :::
  ::::
- **Switch to the Feature Branch**: Check out the new branch in your local development environment.
{% endif %}

{% if page %}##### {% endif %}3. **Create a Merge/Pull Request** 🔄{% if slide %} Push branch to remote and link to Issue (e.g. "Closes #123"){% endif %}
{% if page %}
- **Push the Branch**: Once the feature is complete and tested, push the feature branch to the remote repository.
- **Open a Merge Request**: Create a merge request (MR) or pull request (PR) in your version control system (e.g., GitHub, GitLab, Bitbucket). In the MR/PR:
  - Reference the original issue (e.g., "Closes #123") to link the feature to the issue.
  - Provide a description of the changes made and any relevant context.
  - Specify any additional reviewers or stakeholders.
  :::{note}
  A common suggestion is to create a Merge/Pull Request **after having implemented** the feature (i.e. after [5. **Test the Feature**](#test-the-feature)).
  We recommend to anticipate the creation of the Merge/Pull Request and to mark it as _draft_ until the feature is implemented. In doing so you can use the "News Feed" of the _draft_ Merge/Pull Request to document the development process.
  :::
{% endif %}

{% if page %}##### {% endif %}4. **Develop the Feature** 💻{% if slide %} Implement code following best practices{% endif %}
{% if page %}
- **Implement the Feature**: Write the code to implement the feature as described in the issue.
- **Commit Changes**: Regularly commit your changes with clear and descriptive commit messages that reference the issue number (e.g., "Fixes #123: Implement login functionality").
{% endif %}

{% if page %}##### {% endif %}5. **Keep Branch updated** 🔄{% if slide %} Regularly include changes from the healthy reference{% endif %}
{% if page %}
- **Include changes from healthy reference**: Regularly include any updates of the target branch.
  In practice this boils down to regularly either rebase the feature branch, or merge the target branch.
- **Check compatibility of changes**: Make sure that any changes from the healthy reference branch are compatible with your implementation of the feature.
  :::{warning}
  What state identifies as the healthy reference might change throughout the development of a feature.
  It is up to the developer to assert that merging a feature branch leads again to a healthy state.
  Thus, the feature branch must be compatible with the target branch by the time it is ready to merge, and not when it was created.
  :::
{% endif %}

{% if page %}##### {% endif %}6. **Test the Feature** 🧪{% if slide %} Run tests locally or via automation services{% endif %}
{% if page %}
- **Local Testing**: Test the feature locally to ensure it works as expected.
- **Update Documentation**: If necessary, update any relevant documentation to reflect the new feature.
{% endif %}

{% if page %}##### {% endif %}7. **Code Review** 👥{% if slide %} _"undraft"_ the Merge/Pull Request, designate a reviewer
{% endif %}
{% if page %}
- **Mark the Merge/Pull Request as ready**: Remove the _"draft"_ status from the Merge/Pull Request

  ::::{note}
  Usually the option is to be found in the News Feed of the Merge/Pull Request:
  :::{card} <i class="fab fa-github"></i> **GitHub**
  Here the option is called {bdg-primary}`Ready for review`
  :::
  :::{card} <i class="fab fa-gitlab"></i> **GitLab**
  Here: {bdg-primary}`Mark as ready`
  :::
  ::::
- **Review Process**: Team members review the merge request, providing feedback and suggestions.
- **Make Revisions**: Address any feedback by making necessary changes to the code and pushing updates to the feature branch.
{% endif %}

{% if page %}##### {% endif %}8. **Merge the Feature** ✅{% if slide %} Merge the approved request closing the related Issue{% endif %}
{% if page %}
- **Approval**: Once the merge request is approved, merge the feature branch into the main branch.
- **Close the Issue**: After merging, close the original issue to indicate that the feature has been completed.
{% endif %}
