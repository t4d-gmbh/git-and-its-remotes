#### Activity Tracking

:::{admonition} A {octicon}`git-pull-request;0.8em` News Feed {math}`\neq` <i class="fab fa-git"></i> history
:class: warning, margin

Activity-tracking is a feature of remote service platforms {%if page %}such as <i class="fab fa-github"></i> **GitHub** and <i class="fab fa-gitlab"></i> **GitLab** that offer, {% endif %}and not a <i class="fab fa-git"></i> concept in itself.
"News Feeds" might contain parts of the <i class="fab fa-git"></i> history, but not vice-versa.
:::
{% if slide %}
GitHub, GitLab, and others perform activity tracking, providing a full list of changes that includes a full history of what happened, when it happened, and why it happened.
{% else %}
One of the key services offered by GitHub, GitLab, and others is tracking and providing a full record in an organised way of all the changes beyond the commits history provided in Git.
More than just keeping a list of changes, it includes a full history of what happened, when it happened, and why it happened. 

Tracking activities is available both for {octicon}`issue-opened;0.8em` Issues and {octicon}`git-pull-request;0.8em` Merge/Pull Requests and is reported in the attached "News Feed" that can also be used for commenting.
Despite the automated activity tracking it is also possible to manually create links between Issues and/or Pull/Merge Requests simply by pasting their URL as a comment in some News Feed. 

By means of this automated tracking the complete life-cycle is documented which can drastically facilitate collaboration and documentation, as these "News Feeds" effectively turn into a digital logbook.
{% endif %}


Key advantages:

1. **Clarity and Transparency**: understand what has been done in a repository and why and by whom, even after months or years.
{% if page %}
   Every time something in the project is changed GitHub/GitLab records:
    
   - What changed, i.e. the actual lines of code;
   - Why it changed through issue tracking and pull requests:
   - Who changed it
{% endif %}
1. **Accountability and Responsibility**: by tracking who made changes and why makes it addressing problems easier and faster

1. **Collaboration and Communication**: the full history of changes ensures everyone is on the same page{% if page %}, even in teams working remotely or in different time zones.
The Pull/Merge Requests system encourages discussions and reviews within a team or a wider community{% endif %}. 

1. **Continuous learning and preventing mistakes**: a full history or every issue, change, and discussion, new users or future develops can look back and learn why certain decisions were made{% if page %}, what worked and what didn’t, or how similar problem were solved, which in turn allows for better informed decision-making in the future{% endif %}.

1. **Gather Contextual Information**: extending the <i class="fab fa-git"></i> with contextual information facilitates the identification of a previous healthy state or breaking changes in dependencies{% if page %} thus making it easier to recover from mistakes, quickly identify or even prevent bug introduced external changes{% endif %}.

1. **Efficiency and Trust-Building**: keep track of an open discussion directly where the changes are made makes it easier to find information and builds trust{%if page %} (vs. long-chains of e-mails and endless meetings){% endif %}.

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2
:hidden:

./newsfeed_vs_githistory
```
{% endif %}
