# 🎬 Day 7: CSS Transformations, Transitions, and Hierarchy

## 🔄 Transform and Transition Examples
```css
.box:hover {
  transform: rotate(45deg) scale(1.2);
  transition: transform 0.5s ease-in-out;
}
```

## 🏅 CSS Specificity and Inheritance
- Specificity: `!important` > Inline > ID > Class > Element > Inheritance
```css
div {
  color: blue !important; /* Highest priority */
}
```