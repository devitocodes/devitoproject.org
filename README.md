# devitoproject.org website


This repo contains the source files and deployment for [devitoproject.org](devitoproject.org). The website is built with:

- [quartodoc](https://github.com/machow/quartodoc) for the automatic generation of the API reference. See the repo for installation and usage.
- [quarto](https://quarto.org/) for the website itself. See their documentation for installation and specifics. This is built on top of pandoc and supports all pandoc standard syntax plus additional scientific writing tools.


The website is fully described through the markdown `.qmd` files for the pages and `_quarto.yml` for the layout. You can also preview the website locally when making changes running 

```bash
quartodoc build
```

to generate all the API reference files then

```bash
quarto preview
```

to create the preview of the website that will automatically open in your browser.