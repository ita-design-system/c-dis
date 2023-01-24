---
title: Direction
description: Modifieurs relatifs à la propriété dis-direction
layout: libdoc/page-split
order: 500
---
```html
<h2>m-column</h2>
<p>Pour <strong>dis-direction: column</strong></p>
<div class="c-dis">
    <div>Item 1 <br><strong>sans modifieur m-column</strong></div>
    <div>Item 2 <br><strong>sans modifieur m-column</strong></div>
    <div>Item 3 <br><strong>sans modifieur m-column</strong></div>
</div>
<div class="c-dis m-column">
    <div>Item 1 <br><strong>avec modifieur m-column</strong></div>
    <div>Item 2 <br><strong>avec modifieur m-column</strong></div>
    <div>Item 3 <br><strong>avec modifieur m-column</strong></div>
</div>

<h2>m-column-reverse</h2>
<p>Pour <strong>dis-direction: column-reverse</strong></p>
<div class="c-dis m-column-reverse">
    <div>Item 1 <br><strong>avec modifieur m-column-reverse</strong></div>
    <div>Item 2 <br><strong>avec modifieur m-column-reverse</strong></div>
    <div>Item 3 <br><strong>avec modifieur m-column-reverse</strong></div>
</div>

<h2>m-row-reverse</h2>
<p>Pour <strong>dis-direction: row-reverse</strong></p>
<div class="c-dis m-row-reverse">
    <div>Item 1 <br><strong>avec modifieur m-row-reverse</strong></div>
    <div>Item 2 <br><strong>avec modifieur m-row-reverse</strong></div>
    <div>Item 3 <br><strong>avec modifieur m-row-reverse</strong></div>
</div>

<h2>Exemples responsive</h2>
<p>L'exemple suivant s'affiche en colonne sur la taille d'écran xs.</p>
<div class="c-dis" m-column="xs">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>
<p>L'exemple suivant s'affiche en rangée inversée sur la taille d'écran xs.</p>
<div class="c-dis" m-row-reverse="xs">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>
<!-- DEMO UNIQUEMENT -->
<style>
    body {
        padding: var(--ita-spacing-4);
        background-color: var(--ita-color-primary-900);
        color: var(--ita-color-primary-200);
        font-family: var(--ita-font-family-mono);
        font-size: 1rem;
        line-height: 1.5rem;
        padding-bottom: 50vh;
    }
    .c-dis {
        background-color: var(--ita-color-primary-800);
    }
    .c-dis > * {
        background-color: var(--ita-color-primary-500);
        color: var(--ita-color-primary-900);
        border: var(--ita-border-6);
        padding: var(--ita-spacing-4);
    }
    .c-dis + .c-dis {
        margin-top: var(--ita-spacing-4);
    }
    .c-dis + h2 {
        margin-top: var(--ita-spacing-12);
    }
</style>
```
{:.playground title="Modifieurs dis-direction"}


