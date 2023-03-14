---
title: Flexbox wrap
description: Modifieurs relatifs au retour à la ligne et à l'ordre d'affichage
layout: libdoc/page-split
order: 140
---
```html
<h2>m-flex m-wrap</h2>
<p>Par défaut, le retour à la ligne est <strong>désactivé</strong> sur le composant c-dis. Il est possible de l'activer avec le modifieur m-wrap, pour <strong>flex-wrap: wrap</strong></p>
<div class="c-dis m-flex">
    <div>Item 1 dans un conteneur c-dis <strong>sans modifieur m-wrap</strong></div>
    <div>Item 2 dans un conteneur c-dis <strong>sans modifieur m-wrap</strong></div>
    <div>Item 3 dans un conteneur c-dis <strong>sans modifieur m-wrap</strong></div>
</div>
<div class="c-dis m-flex m-wrap">
    <div>Item 1 dans un conteneur c-dis <strong>avec modifieur m-wrap</strong></div>
    <div>Item 2 dans un conteneur c-dis <strong>avec modifieur m-wrap</strong></div>
    <div>Item 3 dans un conteneur c-dis <strong>avec modifieur m-wrap</strong></div>
</div>

<h2>Exemples responsive</h2>
<div class="c-dis m-flex m-wrap--xs">
    <div>Je passe en wrap en taille d'écran xs</div>
    <div>Item 1 dans un conteneur c-dis <strong>avec modifieur classe CSS</strong></div>
    <div>Item 2 dans un conteneur c-dis <strong>avec modifieur classe CSS</strong></div>
    <div>Item 3 dans un conteneur c-dis <strong>avec modifieur classe CSS</strong></div>
</div>
<div class="c-dis m-flex" m-wrap="xs,sm">
    <div>Je passe en wrap en taille d'écran xs et sm</div>
    <div>Item 1 dans un conteneur c-dis <strong>avec attribut responsive</strong></div>
    <div>Item 2 dans un conteneur c-dis <strong>avec attribut responsive</strong></div>
    <div>Item 3 dans un conteneur c-dis <strong>avec attribut responsive</strong></div>
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
        border: 1px solid var(--ita-color-primary-200);
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
{:.playground title="Modifieurs flex-wrap"}


