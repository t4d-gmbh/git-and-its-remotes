### Merge/Pull Requests

What are merge (pull) requests?

A Merge Request (GitLab) or Pull Request (GitHub) corresponds to a formal request by a developer to have their code changes merged from one branch (e.g. to develop a new feature or fix a bug) into another branch (usually the main).

In a collaborative project, it is a useful tool for:
- Review code changes before merging
- Discuss changes and suggest improvements
- Testing code to ensure changes don’t break the project or the overall workflow.
- Approve code changes or workflow (by one or several developers).


What are the key components of a Pull/Merge Request?
1. Source branch (containing the new changes) and Target branch (where the changes are merged into, main or develop)
2. Description: a title and a brief description outlining the changes made in the branch, which can be linked to issues or tasks to provide context
3. Reviewers: team members to review the changes an provide feedback
4. Comments: a discussion thread or inline comments on specific lines of codes
5. Approval / Request changes: Reviewers either approve the changes or request further modifications
6. CI/CD Integration: automated checks are triggered to validate the code
7. Merge: process of incorporating the changes into the target branch
8. Conflict resolution: merge conflicts (i.e. when changes in the source branch contradict changes in the target branch) that might need to be resolved


Pull / Merge Request workflow:
1. Create branch
2. Commit changes (any work done on the branch)
3. Push branch into remote repository
4. Create Pull / Merge Request to propose the changes from the source to the target branch
5. Review and Feedback, requesting additional changes as needed
(6. Automated Testing run to ensure the changes don’t introduce bugs or other problems)
7. Approval
8. Merge changes into target branch


