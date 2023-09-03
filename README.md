# Josh Minkus' Website

Artworks and texts are stored and referenced from `/_artworks` and `/_texts` respectively.

Artworks and texts are [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) formatted and have required front matter properties:
- `title`
- `date` (must be ISO 860 format: YYYY-MM-DD)
- `key_image` (required for artworks only, enter image filename only)

Images are stored in and referenced from `/assets/images`.

Reference images in markdown files with the markup: `{% include image.html src="image.jpg" %}` where image's file name is `image.jpg`.

Edit `info.md` to edit info page.