# inuit-base.underline
Underline style that work with [InuitCSS framework](www.inuitcss.com).

**This is a work in progress!** Do not use it in production.

## Underline and fonts

Underline settings (position & width) may work for one font. If your website use
a second font for the headings for example. You may add custom files like
`componment.underline-headings.scss`

```scss
/**
 * Underline for headings
 * Because they use a second font
 */
h1,
.alpha,
h2,
.beta,
h3,
.gamma,
h4,
.delta,
h5,
.epsilon,
h6,
.zeta {
  & a.#{$inuit-underline-namespace}underline {
    @include underline($underline-link-color, 1px, 1px);
    &:hover {
      @include underline($underline-link-color--hover, 1px, 1px);
    }
  }
}
```
