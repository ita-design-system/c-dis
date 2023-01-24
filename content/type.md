---
title: Inline
description: Modifieurs inline pour c-dis
layout: libdoc/page-split
order: 150
---
```html
<div class="c-dis">c-dis<br> Je suis un c-dis standard</div>
<div class="c-dis">c-dis<br> Je suis un autre c-dis standard</div>
<div class="c-dis m-inline-dis">c-dis m-inline-dis<br> Je suis un c-dis inline</div>
<div class="c-dis m-inline-dis">c-dis m-inline-dis<br> Je suis un autre c-dis inline</div>
<!-- DEMO UNIQUEMENT -->
<style>
    body {
        padding: var(--ita-spacing-4);
        background-color: var(--ita-color-primary-900);
        color: var(--ita-color-primary-200);
        font-family: var(--ita-font-family-mono);
        font-size: 1rem;
        line-height: 1.5rem;
        min-height: 100vh;
    }
    .c-dis {
        background-color: var(--ita-color-primary-500);
        color: var(--ita-color-neutral-900);
        padding: var(--ita-spacing-4);
    }
    .c-dis + .c-dis {
        margin-top: var(--ita-spacing-4);
    }
</style>
```
{:.playground title="Modifieurs inline-dis"}


