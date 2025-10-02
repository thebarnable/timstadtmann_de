# thebarnable's webpage

## Local development

```bash
git clone git@github.com:thebarnable/academia-hugo.git # clone the repository
npm run project-setup # setup project
npm run dev # start local dev server
```

## Icon

Website icon is FontAwesome's [microchip](https://fontawesome.com/icons/microchip?f=classic&s=solid).
Converted to 32x32 via `rsvg-convert -w 32 -h 32 microchip-solid-full.svg -o icon32.png`, recolored via `convert icon32.png   -fill "#f08c3aff" -opaque black -background black -alpha remove icon32_c.png`

## License

The website theme `Hugo Academia` was designed by [Themefisher](https://themefisher.com) & developed by [Gethugothemes](https://gethugothemes.com).
This repository is based on the [Hugo Academia theme](https://github.com/gethugothemes/academia-hugo).
All contents within the `content` and `config` folders were adapted/rewritten, with some additional changes throughout the repo.

Released under the [MIT license](https://github.com/thebarnable/academia-hugo/blob/master/LICENSE.md).
