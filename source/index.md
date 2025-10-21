```{include} ../README.md
:end-before: <!-- include-upper -->
```

{% if build == "slides" %}
:::{admonition} Authors
:class: note, margin
Dr. Jonas I. Liechti  
Dr. Matteo Delucchi
:::

:::{admonition} Editors
:class: note, margin
Barbara Mejia
:::
{% else %}
### Authors

**Dr. Jonas I. Liechti**  
**Dr. Matteo Delucchi**

### Editors

**Barbara Mejia**  
{% endif %}

### Content
```{toctree}
:maxdepth: 1
{% if build == "slides" %}:numbered:{% endif %}

content/index
```
