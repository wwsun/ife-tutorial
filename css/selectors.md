# Selectors

## Pseudo Class Selectors

### Link-related pseudo class selectors

- `:link` - same as `a[href]`
- `:visited`
- `:hover`
- `:active` - being clicked on or otherwise activated

Tip: **[LOVE HATE](http://css-tricks.com/remember-selectors-with-love-and-hate/)** 

### Input & link related pseudo class selectors

- `:focus` select links that are the current focus of the keyboard
- `:target` match when the hash tag in the current URL matches that ID
- `:enabled`
- `:disabled`
- `:checked`

### Position/number-based pseudo class selectors

- `:root` root of document, `<html>` element
- `:first-child`
- `:last-child`
- `:nth-child(N)`

### Text-related pseudo class selectors/elements

- `::first-letter`
- `::first-line`
- `:lange` match anyhting that either has or is a descendant of an element with a matching lang attribtue

### Content-related pseudo "elements"
- `::before` add content before a certain element
- `::after` add content after a certain element

> **Pseudo elements:** they don't select any "real" element that exists on the page.

## Links

1. [CSS Pseudo Class Selectors](https://css-tricks.com/pseudo-class-selectors/)