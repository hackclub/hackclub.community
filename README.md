# hackclub.community

How to add a new project
------------------------

This site is a small static page. Projects are listed in `index.html` inside the `.projects` container. Follow these steps to add a new project entry:

1. Open `index.html` and find the `<div class="projects">` block.
2. Add a new `<li>` inside the `<ul>` using the same structure as existing entries. Use semantic tags (no custom tags like `<p1>`).

Recommended HTML snippet to copy/paste:

```html
<li>
	<h3><a href="https://example.com">Project Name</a></h3>
	<div class="project-row">
		<img src="https://.../image.png" class="hctv" alt="Project screenshot">
		<div class="project-info">
			<p>Short one-line description of the project.</p>
			<span class="meta">Optional meta text</span>
		</div>
	</div>
</li>
```

Notes and tips
- Keep images reachable (hosted with HTTPS). The site uses the `.hctv` class for sizing; adjust `style.css` if you need a different width.
- Use clear `alt` text for accessibility.
- Preview changes by opening `index.html` in your browser (double-click the file or use a simple local server).
- Commit with a descriptive message, e.g. `Add: Hack Club TV project entry`.

If you want the project layout adjusted (different image width, stacked layout on mobile, etc.), edit `style.css` and test in your browser.

Questions? Reply with the project name, description, and image URL and I can add it for you.
