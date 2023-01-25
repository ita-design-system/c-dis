---
title: Flexbox axe cross
description: Modifieurs flexbox pour l'axe secondaire "cross"
layout: libdoc/page-split
order: 300
---
```html
<h2>m-flex m-cross-start</h2>
<p>Pour <strong>align-items: flex-start</strong></p>
<div class="c-dis m-flex">
    <div>Item 1</div>
    <div>Item 2<br> Avec une ligne en plus <br>pour visualiser l'effet</div>
</div>
<div class="c-dis m-flex m-cross-start">
    <div>Item 1</div>
    <div>Item 2<br> Avec une ligne en plus <br>pour visualiser l'effet</div>
</div>

<h2>m-flex m-cross-center</h2>
<p>Pour <strong>align-items: dis-center</strong></p>
<div class="c-dis m-flex m-cross-center">
    <div>Item 1</div>
    <div>Item 2<br> Avec une ligne en plus <br>pour visualiser l'effet</div>
</div>

<h2>m-flex m-cross-end</h2>
<p>Pour <strong>align-items: dis-end</strong></p>
<div class="c-dis m-flex m-cross-end">
    <div>Item 1</div>
    <div>Item 2<br> Avec une ligne en plus <br>pour visualiser l'effet</div>
</div>

<h2>m-flex m-cross-baseline</h2>
<p>Pour <strong>align-items: baseline</strong>, alignement sur le bas de la première ligne de texte.</p>
<div class="c-dis m-flex m-cross-baseline">
    <div><h1>Item 1</h1></div>
    <div><h3>Item 2</h3><br> Avec une ligne en plus <br>pour visualiser l'effet</div>
    <div><h6>Item 3</h6></div>
</div>

<h2>Exemple responsive</h2>
<p>cross-end sur taille d'écran xs et cross-start sur taille d'écran sm</p>
<div class="c-dis m-flex" m-cross-end="xs" m-cross-start="sm">
    <div>Item 1</div>
    <div>Item 2<br> Avec une ligne en plus <br>pour visualiser l'effet</div>
</div>
<!-- DEMO UNIQUEMENT -->
<style>
    body {
        padding: var(--ita-spacing-4);
        background-color: var(--ita-color-primary-100);
        color: var(--ita-color-primary-800);
        font-family: var(--ita-font-family-mono);
        font-size: 1rem;
        line-height: 1.5rem;
        padding-bottom: 50vh;
    }
    .c-dis {
        background-color: var(--ita-color-primary-200);
    }
    .c-dis > * {
        background-color: var(--ita-color-primary-500);
        color: var(--ita-color-primary-100);
        border: var(--ita-border-6);
        padding: var(--ita-spacing-4);
    }
    .c-dis + .c-dis {
        margin-top: var(--ita-spacing-4);
    }
    .c-dis + h2 {
        margin-top: var(--ita-spacing-12);
    }
    /* Pour la démo baseline */
    .c-dis h1::after {
        content: '';
        position: absolute;
        display: block;
        width: 80vw;
        height: 1px;
        background-color: var(--ita-color-neutral-900);
    }
</style>
```
{:.playground title="Modifieurs flexbox pour l'axe cross"}


