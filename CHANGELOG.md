# Changelog

### 1st April 2017

With Hugo v0.20 the `.Now` is deprecated and will be replaced by the `now` template function. v0.19 does support both and as part of the transition phase. Hence the least required version of Hugo is v0.19.

### 28th October 2016 - Option to link custom assets

You're now able to link local or external assets by adding their url to
the `custom_js` and `custom_css` variables in the config file.

[Show me the diff](https://github.com/digitalcraftsman/hugo-icarus-theme/commit/cd1a8c02e0cf97c443cfdbf44091e66863305eba)

### 8th March 2016 - Options to disable features for single pages

#### Comments

The comment section can be disabled for single pages in the frontmatter.

[Show me the diff](https://github.com/digitalcraftsman/hugo-icarus-theme/commit/c7dcfa6548cc71c48d39bba6367aea7d15203b37)

#### Profile and widgets

The profile and the widgets can be disabled for single pages in the frontmatter. Are both disabled the content will use the full width of the page

[Show me the diff](https://github.com/digitalcraftsman/hugo-icarus-theme/commit/d0fcabe2fbd5e0d5d6f29b6c8d19699e5b11fdde)


### 3rd January 2016 - Allow specifying an avatar

This change adds the new variable `avatar` under `[params]` in the configuration. You need to set this path in order to show an avatar image. The default one can still be found under `css/images/avatar.png`.

[Show me the diff](https://github.com/larrywright/hugo-icarus-theme/commit/0850eabae7e7f79151bfcb462d4ad6795d7caeea)


### 27th November 2015 - Upgrade to Hugo v0.15

Hugo v0.15 is required in order to run the theme with the changes listed below:

#### Google Analytics template

The setup of Google Analytics changed slighty due to the switch to Hugo's built-in template. In order to update the theme you need to relocate thr `google_analytics` variable in the configs and rename it to `googleAnalytics`. Take a look in the example [`config.toml`](https://github.com/digitalcraftsman/hugo-icarus-theme/blob/dev/exampleSite/config.toml).

[Show me the diff](https://github.com/digitalcraftsman/hugo-icarus-theme/commit/fa50238040577c80b5871772cf944681ccfc075f)


### 18th October 2015 - Rename i10n to l10n

Since the right shortcut of localization is "l10n" and not "i10n" (from internationalization) I renamed the shortcut in all places of the theme. The most significant change is the renaming of the `i10n.toml` file inside the `data` folder to `l10n.toml`. This has the side effect that all key paths used for l10n changed within the templates too.

[Show me the diff](https://github.com/digitalcraftsman/hugo-icarus-theme/commit/f52c1da20d8daed67bc2d51627bfe00c7a7b158e)
