# CSS Lessons Learned

## Specific

* Styles applied to ids are more specific than classes and will win.

* Only use id-s if you have to (e.g. for Javascript integration)

* Last style definition wins

* A more specific selector will win over a less specific one. *ul li a* is more
specific than *li a*

* Avoid using *!important*  at all cost.

## Selectors

* Keep them max 3 levels deep.

## Color

* [Named-colors-and-hex-equivalents](https://css-tricks.com/snippets/css/named-colors-and-hex-equivalents/)

## Percentages height or width

* Are always relative to their containers. Who should have height or width defined too for it to work.

## Font size: use em or rem

* 1 em equals 1 * the default font size in pixels of the parent element (default is 16px). So 2em equals 32px. Works with inheritance. rem always calculates from the html element.

## Fonts : rule of thumb

* Use relative units for text, simply pick random numbers that set the font sizes somewhat close to what your design calls for (seriously).
