#### News Feed ⚡ <i class="fab fa-git"></i> History

{% if build == "pages" %}

The <i class="fab fa-github"></i> or <i class="fab fa-gitlab"></i> News Feed provides a broad overview of recent activities, the <i class="fab fa-git"></i> History provides a detailed and structured view of the project’s evolution. 
Both tools help to track changes, discuss ideas, understand references to related topic (issues, merge/pull requests, etc.) and make project management and collaboration more efficient.

##### News Feed

The <i class="fab fa-github"></i> News Feed provides a high-level overview of activities in the repositories. 
It includes updates such as new commits, pull requests, issues, and comments.
This feed is useful for quickly catching up on recent changes and interactions within the project but also for getting a sense of the project's overall activity and progress.
Additionally, it can help you stay informed about the work being done by other contributors and provide opportunities for collaboration and feedback.

![GitHub News Feed](./github_news_feed_new.png)

##### <i class="fab fa-git"></i> History

<i class="fab fa-git"></i> History, on the other hand, offers a detailed view of the changes made to your codebase locally and remotely.
It provides a chronological record of commits, branches, merges, and other actions that have occurred throughout the project's history.
By using commands like `git log`, you can visualize the commit history in a concise and graphical format. 
This is particularly useful for understanding the sequence of changes and how different branches and merges have evolved over time.
It also allows you to navigate through the project's history, compare different versions of the code, and identify the changes that have been made by you and other contributors without the need for a web interface.
This can be helpful for debugging issues, reverting changes, and understanding the context of specific commits.

![Git Log Graph](./git_log_graph_new.png)

Compared to the News Feed, it does not provide real-time updates or notifications about recent activities and interactions.

{% else %}

::::{grid}
:::{grid-item-card} News Feed
**Repository activities** (commits, pull requests, issues, comments). 
Useful for *updates* and *collaboration*.
![GitHub News Feed](./github_news_feed_new.png)
:::
:::{grid-item-card} <i class="fab fa-git"></i> History
Record of **codebase changes** (commits, branches, merges). 
Useful for understanding project *evolution* and *debugging*.
![Git Log Graph](./git_log_graph_new.png)
:::

{% endif %}
