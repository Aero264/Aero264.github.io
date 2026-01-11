To alter page text width, modify max-width property in css/compiled/main.css:
max-w-prose {
  max-width: none;
}

To make page headings bold and not extrabold, set font-bold for header-h1 in layouts/_default/single

To make page sitename bold and not extrabold, set font-bold for h1 in layouts/partials/profile
To make page site headline semibold, set font-semibold for h2 in layouts/partials/profile

To allow inline html, set the following in hugo.toml:
[markup]
  [markup.goldmark]
    [markup.goldmark.renderer]
      unsafe = true

Field-specific tagging available in the layouts/shortcodes/tag and assets/css/custom.css