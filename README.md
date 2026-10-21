# CSS and Website Notes

CSS (Cascading Style Sheets) is the language used to control how HTML content looks and is arranged. It separates presentation from page content, helps keep a consistent design across pages, and supports responsive layouts for different screen sizes.

In `style.css`, the `.button-link` rule styles a call-to-action link: the **selector** is `.button-link`, the **property** is `background-color`, and the **value** is `#193536`. Together, they give matching links a dark teal background.

CSS can be added inline with a `style` attribute on an HTML element, embedded inside a page's `<style>` element, or stored in an external `.css` file linked with `<link>`. Inline CSS affects the element carrying the attribute; embedded CSS applies to its page; external CSS can be reused across multiple pages and is easier to maintain. This website uses embedded CSS in `information.html` and the external `style.css` on the home and inquiry pages.

CSS1 introduced core styling such as colors, fonts, and margins. CSS2 added capabilities including positioning and media-specific styles; CSS 2.1 refined and clarified the specification. Modern CSS is modular: separate specifications cover features such as layout, selectors, and color, allowing them to evolve independently.

Browser support matters because browsers can implement newer CSS features differently, which may affect appearance and usability. The website was tested in **Google Chrome** and **Microsoft Edge**.

Semantic HTML communicates the purpose of content: `<nav aria-label="Main navigation">` identifies navigation. A `<div class="hero-copy">` is non-semantic; it groups content without describing its meaning, so use it when no more suitable semantic element applies.
