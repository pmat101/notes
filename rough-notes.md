# कर्म कर, फल की चिंता न कर..

## HTML, CSS n JavaScript

1. 💀HTML, 👩🏻‍🦰CSS, 🧠JS; response codes: ✔︎200, ✘404, ✕500; `<video>` tag

2. extensions: VSCode icons, Chai theme, prettier, live preview; FIVERR- buyer request

3. `<meta>` tags: keywords, description

4. h1-h6; `option + shift + ↓` to copy a line; `option + ↓` to move text down; hold _option_ key to apply multiple cursors; inline CSS; link tags; `<p>` tags

5. `<img>` tag; _height/width_ attributes; table, rowspan/colspan attributes; <br>; ordered list, unordered list, definition list

6. faster loading pages get ranked higher by search engines, CLS (cumulative layout shift) should be less, LCP (largest contentful paint) ie. the biggest element of the page should load within 2.5s, FID (first input delay) any input element should process within 100ms; use chrome lighthouse to analyze page load; make page title and meta description very detailed (meta keywords have been depricated); **refer web.dev for more info**

7. form

8. inline vs block elements

9. id vs classes

10. `<video>` tag attributes: src, width/height, controls, autoplay, loop, muted, poster (works as a thumbnail); `<audio>` tag attributes: src, controls, autoplay, loop, muted, preload; `<iframe>`

11. Semantic tags: [header > nav] - [main > section > article > figure] - aside - footer

12.

13. HTML Entities; `<pre>`, `<blockquote>` tags

14.

15. inline, internal and external CSS

16.

17. tag selector, class selector, id selector, child selector (parent > child), descendant selector (parent child), universal selector (\*), pseudo selector (:visited/:link/:active/:hover/:first-child)

18. `box-sizing: border-box` makes total dimensions of an element include _padding_ and _border_; **margin collapse** - 2 element on top of each other, the one with bigger margin will be applied

19. Text related properties: font-family, font-style, font-weight, font-size, line-height, text-transform, text-decoration, text-decoration-thickness, text-indent, text-overflow (used with `overflow: hidden`), word-break, text-align

20.

21. CSS specificity: !important > inline style > id > class/attribute > tagName > universal

22. margin: auto; px, vw, vh, em (relative to parent), rem (relative to root element), min-width, min-height, max-width, max-height, % (relative to parent)

23. _inline_ elements can't have margin/padding at the top or change in width, for that we must make `display: inline-block`; `visibility: hidden` vs `display: none`

24. `box-shadow: h-position v-position blur size color inset`; _text-shadow_; _outline_ (placed outside the box model)

25. `list-style: none`; `list-style-position: inside`; `list-style-type: "🙉"`

26. **Overflow**: _scroll_, _auto_, _hidden_, _clip_; `whitespace: no-wrap` (text stays in one line)

27.

28. **Position**: _static_, _relative_, _absolute_, _sticky_, _fixed_; `z-index: 1`

29.

30. **CSS Variabels**: `:root{ --blue: #00f; --p: 1em; }`, now to use these variables `h1{ color: var(--blue); padding: var(--p); }` _:root creates global variables_

31. **Media Queries**: `@media only screen and (max-width: 500px)`

32.
33.

34. **Float** makes an element move left/right and subsequent elements move underneath it except text, **Clear** prevents elements from moving underneath a floating element

35. _more selectors_ 👉 :first-line, :nth-child(even), :before, :after, ::selection, ::first-letter, input::placeholde

36.
37.

38. **Flex Container properties** 👉 `display: flex`, `justify-content: center/flex-start/flex-end/space-around/space-between/space-evenly`, `align-items: baseline/"`, `flex-direction: column/column-reverse/row/row-reverse`, `flex-wrap: wrap/wrap-reverse`, _align-content_ (used to align wrapped content), `gap`; **Flex Item properties** 👉 `order`, `align-self` (align a single item differently), _flex-grow or flex-shrink_ (allow items to increase/decrease in size at different speeds)

39. **Grid Container properties** 👉 `display: grid`, _grid-template-columns_, _grid-template-rows_, _grid-template-areas_, _fr_ units are used to split items in fractions, {align-items/justify-items to place item within cell and align-content/justify-content to place grid within container}; **Grid Item properties** 👉 _grid-row_, _grid-column_ (specifies how much an item will span)

40.
41.

42. **transform**: _rotate_, _scale_, _skew_, _translate_ (transform-origin changes the focal point)

43.
44.
45.
