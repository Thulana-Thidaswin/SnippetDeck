# BBCode Snippet Manager

A simple tool to copy pre-written BBCode snippets with one click.

## ➕ Add New Snippet

1. Add your `.txt` file inside the `snippets/` folder  
2. Go to `main.html`, line 100, and add a new button like this:

```html
<button onclick="copySnippet('your-filename')">Your Label</button>
```

## ▶️ Run the Tool

Open the terminal in this folder and run:

```
python -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

** Make sure you have Python on your computer, if not install it via a tutorial and the version really doesn't matter.
