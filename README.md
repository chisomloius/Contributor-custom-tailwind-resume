Hope You Enjoyed My Resume!
---------

This custom resume was built with HTML, [Tailwind CSS](https://tailwindcss.com/), and the [Universal Résumé Template](https://github.com/WebPraktikos/universal-resume)

How to run it
---------

Navigate to the base directory:

```
cd universal-resume
```

Install the dependencies:

```
npm install
```

Start the development server:

```
npm run serve
```

Only generate CSS that is used on the page which results in a much smaller file size:

```
npm run build
```

Starting Point
---------

`docs/index.html` is the main content file. By copying HTML: add pages, sections, subsection, and other parts.

`npm run build` will make the **docs** directory ready for drag-n-drop to, for example, https://app.netlify.com/drop (free registration required beforehand).

Also, with additionally running `git add docs/styles.css -f` and committing changes, it’s ready for push to GitHub and integration with GitHub Pages. GitHub Pages are free for  public repositories. Under your repository name, not profile, click “Settings” and enable GitHub Pages by navigating to: `Options → GitHub Pages → Source → /docs`.

---------

