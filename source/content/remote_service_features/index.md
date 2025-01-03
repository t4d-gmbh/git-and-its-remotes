## Remote Features

The portfolio of tools offered by different remote services varies between providers. However, some features are nearly universal. {%if page %} and can be roughly described as follows:{% endif %}

{% if slide %}
<!-- BUILDING THE SLIDES -->
```{toctree}
:maxdepth: 2

./universal_features
./web_interface
./collaboration_tools/index
./access
./ci_cd_feature

```
{% else %}
```{include} ./universal_features.md
```
```{include} ./web_interface.md
```
```{include} ./collaboration_tools/index.md
```
```{include} ./collaboration_tools/issues.md
```
```{include} ./collaboration_tools/merge_pull_requests.md
```
```{include} ./collaboration_tools/milestones.md
```
```{include} ./collaboration_tools/labels.md
```
```{include} ./collaboration_tools/activity_tracking.md
```
```{include} ./collaboration_tools/newsfeed_vs_githistory.md
```
```{include} ./collaboration_tools/note_on_collaboration.md
```
```{include} ./access.md
```
```{include} ./ci_cd_feature.md
```
{% endif %}
