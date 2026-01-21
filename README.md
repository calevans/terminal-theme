# Terminal Theme

A terminal-style theme for [StaticForge](https://github.com/eicc/staticforge).

## Installation

This theme is designed to be installed via Composer using the `eicc/staticforge-installer` plugin.

To install this theme into your StaticForge project, run:

```bash
composer require calevans/terminal-theme
```

The installer will automatically detect the package type and install the theme files into:
`templates/terminal/`

## structure

The theme includes:
- **Base Layout**: `base.html.twig`
- **Page Templates**: `index.html.twig`, `category-index.html.twig`
- **Partials**: `partials/`
- **Assets**: `assets/` (CSS, JS, Images)

## Usage

Once installed, configure your StaticForge site to use the `terminal` theme in your `siteconfig.yaml` file:

```yaml
site:
  template: "terminal"
```

If you do not have a `site` section in your config, you can add it at the top level.
