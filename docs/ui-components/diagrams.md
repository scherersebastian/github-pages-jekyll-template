---
layout: default
title: Diagrams
parent: UI Components
nav_order: 6
---

<!-- prettier-ignore-start -->
# Diagrams
{: .no_toc }
<!-- prettier-ignore-end -->

<!-- prettier-ignore-start -->
## Table of contents
{: .no_toc .text-delta }
<!-- prettier-ignore-end -->

<!-- prettier-ignore-start -->

1. TOC
{:toc}
<!-- prettier-ignore-end -->

---

## Mermaid

[Mermaid](https://mermaid-js.github.io/mermaid/#/) lets you create diagrams and visualizations using text and code.

It is a Javascript based diagramming and charting tool that renders Markdown-inspired text definitions to create and modify diagrams dynamically.

## How to

<div class="mermaid">
graph LR;
  A-->B;
</div>
<script async src="https://unpkg.com/mermaid@8.2.3/dist/mermaid.min.js"></script>

## Color scheme

```yaml
# Color scheme supports "light" (default) and "dark"
color_scheme: dark
```

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>
