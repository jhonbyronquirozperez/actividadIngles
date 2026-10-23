# My Jungle Book: The Olympics of My Life

A static one-page website by Jhon Byron Quiroz. It has no build step and no frameworks, only `index.html` and `style.css`.

## Files

```
index.html   page content
style.css    styles
jhon.png     profile photo
```

The introduction video is embedded from YouTube (https://youtu.be/QrGaJMnqmBo), so no video file is needed.

All paths are relative, so keep every file in the same folder.

## Publish on GitHub Pages

1. **Create the repository.** On GitHub, click **New repository**, give it a name (for example `jungle-book`), make it **Public**, and click **Create repository**.
2. **Upload the files.** On the repo page, click **Add file → Upload files**, drag in `index.html`, `style.css`, `jhon.png` and `README.md`, then click **Commit changes**.
3. **Turn on Pages.** Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, then click **Save**.
4. **Open the site.** After a minute or two the URL appears at the top of the Pages settings:
   `https://<your-username>.github.io/<repo-name>/`

## Filling in chapters 4–6

Each of these chapters has its own element with an id in `index.html`, marked with an `EDIT HERE` comment:

| Chapter | Element id |
|---|---|
| 4 - Training and Progress | `chapter-4-content` |
| 5 - Advice for Future Athletes | `chapter-5-content` |
| 6 - Final Reflection | `chapter-6-content` |

Replace the `<p class="placeholder">Coming soon</p>` line inside that element with your text. For example:

```html
<div class="card__content" id="chapter-4-content">
  <p>Your paragraph here...</p>
  <img src="training.jpg" alt="Me studying at night">
</div>
```

Images go in the same folder as `index.html`. They are styled automatically with rounded corners.
