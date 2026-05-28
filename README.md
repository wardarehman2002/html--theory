

````markdown
# HTML Theory Assignment

## Q0. What is HTML and what is the difference between HTML and HTML5?

HTML (HyperText Markup Language) is the standard language used to create and structure web pages.

**Difference:**
- HTML is the older version with limited features.
- HTML5 is the latest version with new features like audio, video, semantic tags, and better support for mobile devices.

```html
<!-- HTML5 example -->
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
````

---

## Q1. What are semantic HTML tags? Why are they important in web development?

Semantic tags clearly describe their meaning to browsers and developers.

**Importance:**

* Improves SEO
* Better readability
* Helps accessibility tools (screen readers)

Examples: `<header>`, `<footer>`, `<article>`

---

## Q2. Difference between `<div>` and `<span>`

* `<div>`: Block-level container
* `<span>`: Inline container

```html
<div>This is a block</div>
<span>This is inline</span>
```

---

## Q3. Block-level vs Inline elements

**Block-level:**

* Takes full width
* Starts on new line
* Example: `<div>`, `<p>`

**Inline:**

* Takes only required space
* Does not start new line
* Example: `<span>`, `<a>`

---

## Q4. Purpose of DOCTYPE declaration

It tells the browser which HTML version is used.

```html
<!DOCTYPE html>
```

It ensures the page runs in standard mode.

---

## Q5. Difference between `id` and `class`

* `id`: Unique for one element
* `class`: Can be used for multiple elements

```html
<div id="header"></div>
<div class="box"></div>
```

---

## Q6. HTML Forms and input types

Forms collect user data.

```html
<form>
  <input type="text">
  <input type="password">
  <input type="email">
  <input type="submit">
</form>
```

Common input types: text, password, email, number, checkbox, radio

---

## Q7. Meta tags and their use

Meta tags provide information about the webpage.

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Used for SEO, responsiveness, and encoding.

---

## Q8. Purpose of `alt` attribute in `<img>`

* Shows text if image fails to load
* Helps screen readers
* Improves SEO

```html
<img src="img.jpg" alt="Beautiful scenery">
```

---

## Q9. Making an image clickable

Wrap image inside an anchor tag.

```html
<a href="https://example.com">
  <img src="img.jpg" alt="Click image">
</a>
```

---

## Q10. Difference between JPG, PNG, SVG, WebP

* JPG: Small size, loses quality
* PNG: Supports transparency
* SVG: Vector, scalable
* WebP: Modern format, small size + good quality

---

## Q11. Semantic tags in HTML5

* `<header>`: Top section
* `<footer>`: Bottom section
* `<section>`: Page section
* `<article>`: Independent content

```html
<article>
  <h2>News</h2>
  <p>Content here</p>
</article>
```

---

## Q12. Difference between `<script>`, async, and defer

* `<script>`: Blocks HTML rendering
* `async`: Loads script asynchronously
* `defer`: Loads after HTML parsing

```html
<script src="app.js" defer></script>
```

---

## Q13. Embedding audio and video in HTML5

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3">
</audio>

<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

---

## Q14. Relative vs Absolute paths

* Relative path: Based on current folder
* Absolute path: Full URL

```html
<img src="images/pic.jpg">
<img src="https://example.com/pic.jpg">
```

---

## Q15. Data attributes (data-*)

Used to store custom data in HTML elements.

```html
<div data-user="123">User Info</div>
```

Used in JavaScript for dynamic features.

---

## Q16. Viewport meta tag purpose

Makes website responsive on mobile devices.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## Q17. How to improve SEO using HTML

* Use semantic tags
* Add meta description
* Use alt attributes
* Proper heading structure (H1, H2, H3)

---

## Q18. Accessibility best practices

* Use alt text for images
* Use semantic tags
* Ensure keyboard navigation
* Use labels in forms

```html
<label for="name">Name:</label>
<input id="name" type="text">
```

---

## Q19. Difference between strong vs b and em vs i

* `<strong>`: Important text (semantic)
* `<b>`: Bold text (visual only)
* `<em>`: Emphasis (semantic)
* `<i>`: Italic (visual only)

```html
<strong>Important</strong>
<b>Bold text</b>
<em>Emphasis</em>
<i>Italic text</i>
```

```

---
