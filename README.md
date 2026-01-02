# HTML-CSS-Notes

## 1. What are the different types of CSS?
- Inline CSS
- Internal CSS
- External CSS

## 2. What is the CSS Box Model?
It consists of: Content, Padding, Border, Margin.

## 3. Difference between class and id?
| class             | id                 |
| ----------------- | ------------------ |
| Can be reused     | Unique             |
| Uses `.`          | Uses `#`           |
| Lower specificity | Higher specificity |

## 4. What is CSS specificity?
It decides which CSS rule is applied when multiple rules target the same element.
```
Inline > ID > Class > Element
```

## 5. Difference between display: none and visibility: hidden?
- display: none → removes element from layout
- visibility: hidden → element takes space but is invisible

## 6. Difference between inline and inline-block?
- inline → cannot set width/height
- inline-block → width/height works

## 7. What is position property?
static (default), relative, absolute, fixed, sticky

## 8. Difference between relative and absolute?
- relative → positioned relative to itself
- absolute → positioned relative to nearest positioned parent

## 9. What is z-index?
Controls stack order of elements. Works only on positioned elements.

## 10. What is Flexbox?
A 1D layout system used to align items in rows or columns.

## 11. Difference between Flexbox and Grid?
| Flexbox         | Grid         |
| --------------- | ------------ |
| 1D layout       | 2D layout    |
| Component-based | Layout-based |

## 13. What is vh and vw?
- vh → viewport height
- vw → viewport width

## 14. What is overflow?
Controls content overflow: hidden, scroll, auto, visible

## 15. What is opacity?
Controls transparency (0 to 1).

## 16. What is !important?
Overrides all other CSS rules (not recommended).

## 17. What is media query?
Used for responsive design.
```
@media (max-width: 768px) {
  body { background: red; }
}
```
## 18. What is pseudo-class?
Defines special states of elements.
```
:hover
:focus
:nth-child()
```

## 19. What is pseudo-element?
Styles specific parts of elements.
```
::before
::after
```
