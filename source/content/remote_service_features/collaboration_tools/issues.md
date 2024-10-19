#### Issues

Issues allow to document and track tasks, bugs and any kind of work that needs to be done in a project.
{% if page %}
Useful in project management, especially in collaborative projects involving multiple developers or an entire community because it allows to track all the changes pertaining to a task.
Issue-tracking is a feature of remote service platforms such as <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab** that offer, and not a  concept in itself <i class="fab fa-git"></i>.
{% endif %}

**![issue](./icons/issue.svg) Issue**
**![mp_request](./icons/mp_request.svg)**

Different types of issues:
- Bug
- Feature requests
- Tasks
- Documentation


What are the key properties of an issue and why are they useful for in collaborative project management?

1. Description: Each issue has a title and a a description section that outline the problem (expected and actual behaviour), task (e.g. steps to reproduce), or an enhancement (e.g. a new feature, potential ideas or solutions to fix a bug) to be made. 
2. Assignees: Issues can be assigned to specific team members to clarify tasks and responsibilities and facilitate project management. 
3. State: to track progress on an issue, they can have descriptive states like “open” (still to be resolved) and “closed” (issue has been resolved), or anything in between like “in progress”.
4. Labels: Issues can be categorised using labels, e.g. “bug”, “documentation”, etc., to help organise and prioritise work.
5. Comments: Team members can discuss an issue in a comment thread to offer insights, feedback, exchange ideas in how to resolve an issue.
6. Milestones: Issues can be grouped under specific milestones and follow the overarching structure of a project, e.g. timeline towards objectives, new version release. 


How to manage issues? Exemplary workflow

1. Open an issue: Person 1 (team member, community user) notices a bug or wants to propose a new feature and opens an issue with a compelling title and a detailed description. 
2. Discussion: Other team members or users discuss potential fixes or features in the comments
3. Assign & Work: someone is assigned (or assign themselves) the issue, and they start working on it in a Git branch. 
4. Comment & Link: When they push commits, they link them to the issue using commit messages
5. Close the issue: Once the code is reviewed and merged, the issue is closed. 
