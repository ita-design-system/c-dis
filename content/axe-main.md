---
title: Flexbox axe main
description: Modifieurs flexbox pour l'axe secondaire "main"
layout: libdoc/page-split
order: 200
---
```html
<h2>m-flex m-main-start</h2>
<p>Pour <strong>justify-content: flex-start</strong>, valeur par défaut qui a le même effet que c-dis m-flex seul</p>
<div class="c-dis m-flex">
    <div>Item 1</div>
    <div>Item 2</div>
</div>
<div class="c-dis m-flex m-main-start">
    <div>Item 1</div>
    <div>Item 2</div>
</div>

<h2>m-flex m-main-center</h2>
<p>Pour <strong>justify-content: flex-center</strong></p>
<div class="c-dis m-flex m-main-center">
    <div>Item 1</div>
    <div>Item 2</div>
</div>

<h2>m-flex m-main-end</h2>
<p>Pour <strong>justify-content: flex-end</strong></p>
<div class="c-dis m-flex m-main-end">
    <div>Item 1</div>
    <div>Item 2</div>
</div>

<h2>m-flex m-main-space-between</h2>
<p>Pour <strong>justify-content: space-between</strong></p>
<div class="c-dis m-flex m-main-space-between">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>

<h2>m-flex m-main-space-around</h2>
<p>Pour <strong>justify-content: space-around</strong></p>
<div class="c-dis m-flex m-main-space-around">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>

<h2>m-flex m-main-space-evenly</h2>
<p>Pour <strong>justify-content: space-evenly</strong></p>
<div class="c-dis m-flex m-main-space-evenly">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>

<h2>Exemple responsive</h2>
<div class="c-dis m-flex" m-main-space-between="xs,sm">
    <div>space-between sur écran xs et sm</div>
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
{:.playground title="Modifieurs flexbox pour l'axe cross"}


