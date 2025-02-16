---
title: overflow-anchor
slug: Web/CSS/overflow-anchor
tags:
  - CSS
  - Propriété
  - Reference
translation_of: Web/CSS/overflow-anchor
---
{{CSSRef}}

La propriété **`overflow-anchor`** permet d'éviter, lors du défilement, que le navigateur ajuste la position afin de minimiser le déplacement du contenu.

Ce comportement est activé par défaut pour les navigateurs qui le prenne en charge. Aussi, cette propriété est uniquement nécessaire lorsque vous rencontrez des problèmes de défilement dans un document et que vous souhaitez désactiver ce comportement.

## Syntaxe

```css
/* Valeurs avec un mot-clé */
overflow-anchor: auto;
overflow-anchor: none;

/* Valeurs globales */
overflow-anchor: inherit;
overflow-anchor: initial;
overflow-anchor: unset;
```

### Valeurs

- `auto`
  - : L'élément peut devenir une ancre lorsque la position de défilement est ajustée.
- `none`
  - : L'élément ne sera pas sélectionné comme ancre.

### Syntaxe formelle

{{csssyntax}}

## Exemples

Pour désactiver l'ancrage du défilement, on pourra utiliser cette propriété :

```css
body {
  overflow-anchor: none;
}
```

## Spécifications

| Spécification                                                                                                    | État                                         | Commentaires         |
| ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | -------------------- |
| {{SpecName('CSS Scroll Anchoring', '#propdef-overflow-anchor', 'overflow-anchor')}} | {{Spec2('CSS Scroll Anchoring')}} | Définition initiale. |

{{cssinfo}}

## Compatibilité des navigateurs

{{Compat("css.properties.overflow-anchor")}}

## Voir aussi

- [Guide sur l'ancrage du défilement (_scroll anchoring_)](/en-US/docs/Web/CSS/overflow-anchor/Guide_to_scroll_anchoring)
