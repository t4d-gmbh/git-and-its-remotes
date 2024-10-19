### Note on Activity Tracking

---

Issue-tracking is a feature of remote service platforms such as <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab** that offer, and not a  concept in itself <i class="fab fa-git"></i>.

the changes pertaining to a task.

{% if page %}
**How to manage issues?**

Exemplary workflow:

1. **Open an issue**: Person 1 (team member, community user) notices a bug or wants to propose a new feature and opens an issue with a compelling title and a detailed description. 
1. **Discussion**: Other team members or users discuss potential fixes or features in the comments
1. **Assign & Work**: someone is assigned (or assign themselves) the issue, and they start working on it either preparing a single commit or creating a separate <i class="fab fa-git"></i> branch. 
1. **Comment & Link**: Progress can regularly be reported by commenting by tagging the issue directly in a commit message.
1. Close the issue: Once the code is reviewed and merged, the issue is closed. 
{% endif %}

---


One of the key services offered by GitHub, GitLab is tracking and providing a full record in an organised way of all the changes beyond the commits history provided in Git. More than just keeping a list of changes, it includes a full history of what happened, when it happened, and why it happened. 

Key advantages:
1. Clarity and Transparency: understand what has been done in a project and why, even after months or years
Every time something in the project is changed GitHub/GitLab records:
	- What changed, i.e. the actual lines of code;
	- Why it changed through issue tracking and pull requests:
	- Who changed it

2. Accountability and Responsibility: by tracking who made changes and why makes it addressing problems easier and faster

3. Organised Problem Solving (Issue Tracking) — cf. previous sub-section

4. Collaboration and Communication: the full history of changes ensures everyone is on the same page, even in teams working remotely or in different time zones. The Pull/Merge Requests system encourages discussions and reviews within a team or a wider community. 

5. Continuous learning and preventing mistakes: By having a full history or every issue, change, and discussion, new users or future develops can look back and learn why certain decisions were made, what worked and what didn’t, or how similar problem were solved, which in turn allows for better informed decision-making in the future.

6. Easy Rollbacks: if a mistake is made, it’s easy to go back to a previous version of the project, reverting to an earlier state without loosing any data.

7. Efficiency and Trust-Building: the ability to comment and keep track of the discussion directly where the changes are made makes it easier to find information (vs. long-chains of e-mails and endless meetings) and foster trusts within a community that a project is being managed carefully at every step of the process.
