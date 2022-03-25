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

Add the import of the mermaid script somewhere:

```
<script async src="https://unpkg.com/mermaid@8.2.3/dist/mermaid.min.js"></script>
```

### Examples

```
<div class="mermaid">
graph TD;
    A[Christmas] -->|Get money| B(Go shopping);
    B --> C{Let me think};
    C -->|One| D[Laptop];
    C -->|Two| E[iPhone];
    C -->|Three| F[fa:fa-car Car];
</div>
```

<div class="mermaid">
graph TD;
    A[Christmas] -->|Get money| B(Go shopping);
    B --> C{Let me think};
    C -->|One| D[Laptop];
    C -->|Two| E[iPhone];
    C -->|Three| F[fa:fa-car Car];
</div>

```
<div class="mermaid">
sequenceDiagram;
    Alice->>+John: Hello John, how are you?;
    Alice->>+John: John, can you hear me?;
    John-->>-Alice: Hi Alice, I can hear you!;
    John-->>-Alice: I feel great!;
</div>
```

<div class="mermaid">
sequenceDiagram;
    Alice->>+John: Hello John, how are you?;
    Alice->>+John: John, can you hear me?;
    John-->>-Alice: Hi Alice, I can hear you!;
    John-->>-Alice: I feel great!;
</div>

```
<div class="mermaid">
gantt;
    title A Gantt Diagram;
    dateFormat  YYYY-MM-DD;
    section Section;
    A task           :a1, 2014-01-01, 30d;
    Another task     :after a1  , 20d;
    section Another;
    Task in sec      :2014-01-12  , 12d;
    another task      : 24d;
</div>
```

<div class="mermaid">
gantt;
    title A Gantt Diagram;
    dateFormat  YYYY-MM-DD;
    section Section;
    A task           :a1, 2014-01-01, 30d;
    Another task     :after a1  , 20d;
    section Another;
    Task in sec      :2014-01-12  , 12d;
    another task      : 24d;
</div>

```
<div class="mermaid">
pie title Pets adopted by volunteers;
    "Dogs" : 386;
    "Cats" : 85;
    "Rats" : 15;
</div>
```

<div class="mermaid">
pie title Pets adopted by volunteers;
    "Dogs" : 386;
    "Cats" : 85;
    "Rats" : 15;
</div>

<!-- Import mermaid js package to create mermaid diagrams -->
<script async src="https://unpkg.com/mermaid@8.2.3/dist/mermaid.min.js"></script>
