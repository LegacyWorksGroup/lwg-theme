# LegacyWorks SCSS Stylesheets Extension For Quarto

This extension includes light and dark mode SCSS stylesheets  for Quarto projects consistent with LegacyWorks colors. Rules are included in all SCSS files for easy text styling and quality-of-life improvements.

## Installing

```bash
quarto add legacyworksgroup/lwg-theme
```

This will install the extension under the `_extensions` subdirectory. If you're using version control, **you must check in this directory**.

## Using

Once you've installed the extension, replace your 'theme' specification in the `_quarto.yml` with `_extensions/legacyworksgroup/lwg-theme/<theme-name>.scss`. Currently, options include:

- `lwg-light.scss` - Light mode consistent with LWG branding
- `lwg-dark.scss` - Dark mode complement of `lwg-light.scss`

## Updating

```bash
quarto update extension legacyworksgroup/lwg-theme
```

This will replace the contents of the `legacyworksgroup/lwg-theme` subfolder of the `_extensions` folder with whatever is in this repository. Note that if you're using GitHub to deploy your Quarto project, you'll need to commit the changes to the extension files for them to take effect.
