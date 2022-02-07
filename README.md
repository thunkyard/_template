# @thunktank/_example

Adapted from [@yhatt/marp-cli-example](https://github.com/yhatt/marp-cli-example)

## Usage

We already have [GitHub Actions workflow](.github/workflows/github-pages.yml) to build and deploy from `master` to `gh-pages` automatically. All you have got to [turn on GitHub Pages with `gh-pages` branch](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) from **"Settings"** tab.

### Edit deck

Just edit **[`PITCHME.md`](./PITCHME.md)**!

#### Preview deck

**[Marp for VS Code]** extension is the best partner for writing Marp slide deck with live preview.

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode">
    <img src="https://raw.githubusercontent.com/marp-team/marp-vscode/master/docs/screenshot.png" width="500" />
  </a>
</p>

**You can try edit and preview on the web now!** Open https://github.dev/yhatt/marp-cli-example/blob/master/PITCHME.md or hit <kbd>.</kbd> key on this repository, and install [Marp for VS Code] extension.

[Marp for VS Code]: https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode

#### Preview via CLI

```bash
npm run start
```

It will be opened preview window via installed Google Chrome, and track change of `PITCHME.md`.

### Assets and themes

- `assets` directory can put your assets for using in the deck. (e.g. Image resources)
- `themes` directory can put [custom theme CSS](https://marpit.marp.app/theme-css). To use in the deck, please change `theme` global directive.

### Build deck via CLI

```bash
npm run build
```

The built assets will output to `dist` folder.

#### Build per assets

```bash
npm run deck      # Output static HTML to dist/index.html
npm run og-image  # Output image for Open Graph to dist/og-image.jpg
```

## LICENSE

[WTFPL](/LICENSE)
