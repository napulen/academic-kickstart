<p align="center"><a href="https://sourcethemes.com/academic/" target="_blank" rel="noopener"><img src="https://sourcethemes.com/academic/img/logo_200px.png" alt="Academic logo"></a></p>

# Academic Kickstart: The Template for [Academic Website Builder](https://sourcethemes.com/academic/)

[**Academic**](https://github.com/gcushen/hugo-academic) makes it easy to create a beautiful website for free using Markdown, Jupyter, or RStudio. Customize anything on your site with widgets, themes, and language packs. [Check out the latest demo](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the showcase](https://sourcethemes.com/academic/#expo).

- A basic setup of a website using the `academic` theme
- The `academic` theme loaded as a submodule on the `themes/academic` path

- 👉 [**Get Started**](#install)
- 📚 [View the **documentation**](https://sourcethemes.com/academic/docs/)
- 💬 [Chat with the **Academic community**](https://spectrum.chat/academic) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@source_themes](https://twitter.com/source_themes) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithAcademic](https://twitter.com/search?q=%23MadeWithAcademic&src=typd)
- 💡 [Request a **feature** or report a **bug**](https://github.com/gcushen/hugo-academic/issues)
- ⬆️ **Updating?** View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)
- :heart: **Support development** of Academic:
  - ☕️ [**Donate a coffee**](https://paypal.me/cushen)
  - 💵 [Become a backer on **Patreon**](https://www.patreon.com/cushen)
  - 🖼️ [Decorate your laptop or journal with an Academic **sticker**](https://www.redbubble.com/people/neutreno/works/34387919-academic)
  - 👕 [Wear the **T-shirt**](https://academic.threadless.com/)
  - :woman_technologist: [**Contribute**](https://sourcethemes.com/academic/docs/contribute/)

The `master` branch of this repository should always point to the latest `master` of the original repo.

If cloning for the first time, add the remote to the original repo:

```bash
git remote add original https://github.com/sourcethemes/academic-kickstart.git
```

The `napulen.github.io` branch of this repository has the changes introduced for generating the website at https://napulen.github.io and it is the default branch

# Migration to newer version of academic

When migrating to a newer version of the `academic` repository.

Sync this `master` and get it up to date

```bash
git checkout master
git pull original master
```

While on that branch, build the newest version of `academic` and make sure it works

```
hugo server
```

Check http://localhost:1313

# Render the full example from academic instead of minimal

The `academic` submodule (`themes/academic`) provides a full demo of the website with several sections and entries.

The version rendered by `academic-kickstart`, however, is minimal.

In order to get the full example working on master, create symbolic links to the example site of `themes/academic`.