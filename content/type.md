---
title: Types de display
description: Modifieurs de la propriété display
layout: libdoc/page-split
order: 150
---
```html
<div class="c-dis">c-dis<br> c-dis seul n'a pas d'effet</div><br>
<div class="c-dis m-inline">c-dis m-inline, display: inline</div><br>
<span class="c-dis m-block">c-dis m-block<br> display: block</span>
<div class="c-dis m-inline-block">c-dis m-inline-block<br> display: inline-block</div>
<div class="c-dis m-flex">c-dis m-flex<br> display: flex</div>
<div class="c-dis m-inline-flex">c-dis m-inline-flex<br> display: inline-flex</div>
<div class="c-dis m-grid">c-dis m-grid<br> display: grid</div>
<div class="c-dis m-inline-grid">c-dis m-inline-grid<br> display: inline-grid</div>
<!-- DEMO UNIQUEMENT -->
<style>
    body {
        padding: var(--ita-spacing-4);
        background-color: var(--ita-color-primary-100);
        color: var(--ita-color-primary-800);
        font-family: var(--ita-font-family-mono);
        font-size: 1rem;
        line-height: 1.5rem;
        min-height: 100vh;
    }
    .c-dis {
        background-color: var(--ita-color-primary-500);
        color: var(--ita-color-neutral-100);
        padding: var(--ita-spacing-4);
    }
    .c-dis + .c-dis {
        margin-top: var(--ita-spacing-4);
    }
</style>
```
{:.playground title="Modifieurs display"}


