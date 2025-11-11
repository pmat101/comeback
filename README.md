# COMEBACK

<!-- Check Harry's notes for each topic: Digital & Hand Written -->

---

## HTML

1. > Server (Backend + Database) -> Browser (HTML + CSS + JS) -> Client (request <-> response)

2. Setup and Extensions, **use buyer request on Fiverr to start freelancing**

3. Head elements has meta tags- title, description etc, live preview on other devices

4. Use option to get multiple cursors, option + shift + down to copy line, use lorem to get dummy text, heading tags, links tags, attributes

5. Images, Lists, Tables

6. _Core Web Vitals_ (check lighthouse report in devtools):

   - CLS (cumulative layout shift) should be low
   - LCP (largest contextual paint) should be max 2.5s
   - FID (field input delay) should be less than 100ms
   - Use relevant title, description and make it responsive
   - refer [Web.Dev](web.dev) for more details

7. Forms - name, value, labels, autofocus, regex, select tag, action, method

8. Inline & Block elements

9. Classes & IDs (IDs can be used for scrolling-linking)

10. SVG, iFrame, Video & Audio (src, controls, width, height, autoplay, loop, muted, poster and preload)

11. Semantic tags: `<header> > <nav>, <aside> - put to side, <main>, <article> - self contained piece, <figure>, <figcaption>, <section> - thematic group, <footer>, <time>`

12.

13. HTML Entities, `<pre>, <q>, <blockquote>, <code>` tags

---

## CSS

14. selecter-declaration format

15. Inline - Internal - External CSS

16.

17. Element, Class, ID, child, descendant, universal and pseudo (link, visited, active, hover, nth-child) selectors

18. **Box-Model**: margin - border - padding - content, element's dimensions exclude margins. **Margin Collapse**: If margins of 2 elements overlap, bigger margin is taken into account

19. Fonts & colours

20.

21. Cascade Algorithm:

    - Position and order
    - Specificity: **!important > inline style > ID > Class > Element > universal > user agent (browser)**

22. Sizing units: px, %, vw, vh, em (inherit from container), rem (inherit from root element `<html>`), vmin, vmax. `min-width, max-height etc.`

23. Use `inline-block` property for inline elements to obey sizing. `display: none` removes element and its space, `visibility: hidden` hides element but keeps its space

24. `box-shadow: h-offset v-offset blur spread color inset;`; _text-shadow_ works similarly

25. list-style, list-style-position, list-style-image

26. **overflow**: auto, scroll, hidden, clip

27.

28. **position**: static, relative (top/ bottom/ right/ left/ z-index can be added), absolute (takes out of normal flow and attaches to nearest positioned ancestor), fixed, sticky

29.

30. CSS Variables:
    `:root {
--var1: value;
--var2: value;
}
// Global variables, local can be created too
background-color: var(--var1, fallback)
// Use`

31. Media Query

32.

33. [Card exercise](./card.html)

~~34. Float & Clear~~

35. More CSS selectors: attribute selector, ::before, ::after, ::selection (add pseudo element dynamically)

36.

37.

38. **FlexBox**

    - Container -> display: flex; justify-content; align-items; decided by _flex-direction_; flex-wrap; align-content;
    - Items -> order; flex-grow; flex-shrink; align-self;

39. **Grid**

    - Container -> display: grid; grid-template-columns; grid-template-rows; grid-template-areas; gap; justify-items; align-items;
    - Items -> grid-row; grid-column; grid-area;

40. [Layout](./layout.html)

41.

~~42. CSS Transforms~~

~~43. [NavBar](./css-nav.html)~~

44.

~~45. CSS Transitions~~

~~46. CSS Animations~~

47.

48.

~~49. object-fit: cover/ contain/ fill; object-position: top right; background-image: url(""); background-position: center center; background-repeat: no-repeat;~~

~~50. filter: blur(10px) / brightness(122%) / greyscale(100%) / invert(1);~~

51.

~~52. Figma~~

~~53. Netflix clone~~

---

## JavaScript

54. alert(), prompt(), confirm(), console.log()

55. var, let, const, object

56. Conditionals & Operators

57. Loops: for, while, do-while, **for-in (loop through object keys), for-off (loop through strings/ arrays)**

58. Arrow Functions are used to pass function as a variable or put it inside another function

59.

60. String methods (strings are immutable), Template Literals: \`string $[] continue..\`

61.

62.

~~63. Arrays: - Array methods: join, push, pop, shift, unshift, toString, delete, concat (creates new array), sort, splice, slice, reverse - For-Each loop - Map: `arr.map((e) => {return e**2})` - Filter: - Reduce:~~

64.

65.

66. DOM (Document Object Model) maps the entire document to an object

67. Children, Parent & Sibling nodes

68. Selecting by IDs, Classes, tagName, querySelector, querySelectorAll

69.

70.

71. innerText, innerHTML, tagName, nodeName (includes everything- comments etc), hidden = true, getAttribute, setAttribute, add, remove, toggle

72.

73.

74. addEventListener, Event Bubbling: If a child is clicked, parent is clicked by default, to stop that use e.stopPropagation(). setTimeOut, setInterval, clearTimeOut, clearInterval

~~75. Advanced Concepts: - JavaScript's core execution is synchronous but when it encounters an asynchronous operation (eg. setTimeout, fetch requests, DOM events), it doesn't wait for it to complete. - **Callback** function is one where a function is passed as an argument instead of the usual variable. - Nested callbacks can easily become complex and hard to maintain and lead to _CallBack Hell!_ - **Promise** is a solution to CallBack Hell. A Promise has 3 parts- _resolve_, _reject_ and _then_, apart from these we also need to
_catch_ for errors. _finally_ is used for cleanup - Promises can be chained using then keyword - Promise.all([prom1, prom2]) can be used to run multiple promises~~

~~76. **Await** is used to wait for an **Async** function to run instead of carrying out pending functions. Await function can be inside Async function~~

77.

~~78.~~

~~79. Try-Catch and error handeling~~

~~80. OOP~~

81.

~~82. Destructuring, Spread Operator, IIFE, Hosting~~

83.

84.

---

<!--

    Heading -    # H1, ## H2, ### H3
    Bold -   **bold text**
    Italic -   _italicized text_
    Blockquote -   > blockquote
    Ordered List -   1. First item, 2. Second item, 3. Third item
    Unordered List -   - First item, - Second item, - Third item
    Code -   `code`
    Horizontal Rule -   ---
    Link -   [title](https://www.example.com)
    Image -   ![alt text](image.jpg)

 -->
