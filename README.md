# tributo-page

[Português](README.pt-BR.md)

A tribute page to goalkeeper Rogério Ceni, built in HTML and CSS as an exercise inspired by the "Build a Tribute Page" project from [freeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/)'s Responsive Web Design curriculum. It is a fan tribute, not affiliated with the player or with São Paulo FC. The page content is in Portuguese.

> **Type:** study project (2023)

![Tribute page](docs/screenshots/tribute.jpg)

## What it has

- Title, a short introduction and a featured illustration.
- Lists with titles won at São Paulo, appearance numbers and goals scored.
- Footer linking to the page author's Instagram.

## How to open

No dependencies or build step. Open `index.html` in a browser or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Structure

- `index.html`: content.
- `style.css`: styles.
- `ceni21.jpg`: main illustration.
- `icone insta.png`: Instagram icon (the file is WebP despite the extension).

## About the data

Figures checked against news sources in 2026: 1,237 matches and 131 goals for São Paulo (61 from free kicks and 69 from penalties), 51 penalties saved and 18 official titles with the club ([Gazeta Esportiva](https://www.gazetaesportiva.com/?p=3394588), [Lance!](https://www.lance.com.br/lancepedia/a-historia-de-rogerio-ceni-no-sao-paulo.html)). The wins (648), clean sheets (418) and the 21 goals in 2005 come from the original version of the page and were not checked. The titles list shows only part of the 18.

## Limitations

- Does not implement every requirement of the freeCodeCamp challenge (for example, the required `id` attributes).
- Not responsive: the image has a fixed 1500 px width and causes horizontal scrolling on smaller screens.

## Credits

- `ceni21.jpg` is a third-party illustration (the artist's signature is on the image); its source is not documented. Get the artist's permission or replace it with a licensed image before reuse.
- Origin of the Instagram icon not documented.

## Security

See [SECURITY.md](SECURITY.md).

## License

No license has been chosen yet; all rights reserved by the author (this does not cover the third-party illustration).
