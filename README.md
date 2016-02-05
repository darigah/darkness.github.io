# GitHub Dark [![tag](https://img.shields.io/github/tag/StylishThemes/GitHub-Dark.svg)](https://github.com/StylishThemes/GitHub-Dark/tags) [![stars](http://github-svg-buttons.herokuapp.com/star.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6)](http://github.com/StylishThemes/GitHub-Dark) [![forks](http://github-svg-buttons.herokuapp.com/fork.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6)](http://github.com/StylishThemes/GitHub-Dark/fork) [![devdeps](https://img.shields.io/david/dev/StylishThemes/GitHub-Dark.svg)](https://david-dm.org/StylishThemes/GitHub-Dark#info=devDependencies)

- Install from [userstyles.org](http://userstyles.org/styles/37035) (with customization options) or [manually](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css).
- Or, install using our [GitHub-Dark (user)Script](https://github.com/StylishThemes/GitHub-Dark-Script) which allows dynamic style updates :bangbang:
- Stylish is available for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/2108/), [Chrome](https://chrome.google.com/extensions/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Opera](https://addons.opera.com/en/extensions/details/stylish/), [Safari](http://sobolev.us/stylish/) and [Firefox Mobile](https://addons.mozilla.org/en-US/firefox/addon/2108/).
- Includes styling for [Octotree](https://github.com/buunguyen/octotree/#octotree) &amp; [ZenHub](https://www.zenhub.io/).
- Use the [grunt build process](https://github.com/StylishThemes/GitHub-Dark/wiki/Build) to customize your GitHub Dark theme.
- Please refer to the [installation documentation](https://github.com/StylishThemes/GitHub-Dark/wiki/Install) for more details.

## Preview
![GitHub Dark preview](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/images/screenshots/after_blue.png)

## [Available Syntax Highlighting Themes](https://stylishthemes.github.io/GitHub-Dark/)

|                      |                        |                          |                 |                       |
|----------------------|------------------------|--------------------------|-----------------|-----------------------|
| Ambiance             | Chaos                  | Clouds Midnight          | Cobalt          | Idle Fingers*         |
| Kr Theme             | Merbivore              | Merbivore Soft           | Mono Industrial | Mono Industrial Clear |
| Monokai*             | Pastel on Dark*        | Solarized Dark*          | Terminal        | Tomorrow Night*       |
| Tomorrow Night Blue* | Tomorrow Night Bright* | Tomorrow Night Eigthies* | Twilight*       | Vibrant Ink           |

\* Supports [Jupyter notebook syntax highlighting](https://github.com/sujitpal/statlearning-notebooks/blob/master/src/chapter2.ipynb)

## Notes

* If you're using a custom domain for GitHub Enterprise, be sure to include it though a `@-moz-document` rule (Firefox) or add it to the `Applies to` section in (Chrome).
* If you want GitHub commit messages to use a monospaced font, and have a background color indicating the width limits, check out [GitHub Commit Limit](https://github.com/StylishThemes/GitHub-Commit-Limit).

## Contributions

If you would like to contribute to this repository, please...

1. Fork
2. Make changes (please read the [contribution guidelines](https://github.com/StylishThemes/GitHub-Dark/blob/master/CONTRIBUTING.md) and abide by them)
3. Create a pull request!

Thanks to all that have [contributed](https://github.com/StylishThemes/GitHub-Dark/graphs/contributors) so far!

## Recent Changes

See the [full change log](https://github.com/StylishThemes/GitHub-Dark/wiki).

#### Version 1.14.50 (2/4/2016)

* Global: Change default background.
* ZenHub: Invert updated ZenHub icons.
* Issues: Add collapsed timeline style. Fixes [issue #284](https://github.com/StylishThemes/GitHub-Dark/issues/284).
* Discussions:
  * Fix 'View More' button on collapsed sections.
  * Fix commit refs in linked commits.
* Organizations:
  * Fix hover in member list.
  * Add repo issues bug icon style (icon added by [Github-show-repo-issues](https://github.com/Mottie/Github-show-repo-issues).
* Gist: Fix logo color.
* Script: Add GHD Script class for styling (icon active matching base color).

#### Version 1.14.49 (1/31/2016)

* Global: Fix OS X emoji invert; see [issue #283](https://github.com/StylishThemes/GitHub-Dark/issues/283).

#### Version 1.14.48 (1/31/2016)

* Global (see [issue #283](https://github.com/StylishThemes/GitHub-Dark/issues/283)):
  * Exclude more hard-to-read unicode codepoints.
  * Handle two more dark emoji.
  * Fix all remaining unicode issues, add generator script.
  * Slightly darken inverted unicode.
  * Yet more unicode fixes, handle image fallback.
  * Fix style, add comment.
  * Apply invert only to unicode fallback images.
