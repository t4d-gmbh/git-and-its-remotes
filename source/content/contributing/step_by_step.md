## Step-by-Step

{% if page %}##### {% endif %}1. **Check Existing Issues** 👀{% if slide %} Check both {octicon}`issue-opened;0.8em` open and {octicon}`issue-closed;0.8em` closed Issues
{% else %} 
   - Browse existing Issues - {octicon}`issue-opened;0.8em` open and {octicon}`issue-closed;0.8em` closed ones - to see if the same or a similar Issue was already created.
   - If your Issue exists already, check for related Merge/Pull Requests and if they implement what you had in mind.
     If not, skip the next step (i.e. don't create a new {octicon}`issue-opened;0.8em` Issue) and simply proceed with step 3. **Read Documentation**.
{% endif %}

:::{admonition} Bugs
:class: warning, margin
Explain how a bug can be reproduced!
:::
{% if page %}##### {% endif %}2. **Open an {octicon}`issue-opened;0.8em` Issues** 📝{% if slide %} Explain why some work needs to be done.
{% else %} 
   - Write a short and concise description of the Bug, Question, or Suggestion.
   - Focus on defining the Issue such that it becomes clear **why some work should be done**.
{% endif %}

{% if page %}##### {% endif %}3. **Read Documentation** 📚{% if slide %} Consult `CONTRIBUTING` and `README.md`.
{% else %}
   - Check for guidelines on how to contribute.
     Usually, they are to be found in a file called `CONTRIBUTING` or in the `README.md`.
   - If unsure, simply stick to this step-by-step workflow
{% endif %}

{% if page %}##### {% endif %}4. **Fork the Repository** 🍴{% if slide %} Create a personal copy of the repository.
{% else %}
   - Create a personal copy of the repository by forking it.
{% endif %}

{% if page %}##### {% endif %}5. **Make Changes** ✏️{% if slide %} Implement in the forked repo. following best practices.
{% else %}
   - Implement the changes or features you want to contribute.
     For smaller changes you might directly work on the healthy reference (i.e. **`main`**) of the forked repository.
     Bigger changes should be implemented in a separate branch following the feature branch approach, for example.
   - Follow the project's coding style and guidelines.
   - Make sure the branch on which you implement the changes, remains up to date with the target branch from to repository.
   - Test and document your changes.
{% endif %}

{% if page %}##### {% endif %}6. **Create a Merge/Pull Request** 🔄{% if slide %} Link it to the related Issue.
{% else %}
   - Go to the original repository and submit a Merge/Pull Request to propose your changes.
   - Follow the guidelines, if present. If not:
     - Link the related issue with a closing statement (e.g. `Closes #123`)
     - Short description of how you addressed the Issue in your changes.
     - Explain why you followed a particular approach (if unclear).
{% endif %}

{% if page %}#### {% endif %}7. **Participate in Code Review** 👥{% if slide %} Be open for feedback and repsect the maintainers decisions.
{% else %}
   - Engage with project maintainers and other contributors during the review process.
   - Be open to feedback and make any necessary revisions.
   - Respect the maintainers decisions and adaptations, if you are not happy with them you can always keep your forked repository and maintain it on your own!
{% endif %}

{% if page %}#### {% endif %}8. 🌟 **Stay Engaged** 🌟{% if slide %}
{% else %}
   - Once the Merge/Pull Request is merged or closed, feel free to delete your fork of the repository. This avoids confusion about which repository is the most up-to-date.
   - Continue to contribute to the project by helping with other issues or discussions.
{% endif %}
