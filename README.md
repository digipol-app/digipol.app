# digipol.app

* github pages docs: https://pages.github.com/
* custom domain docs: https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site
* 404 pages: https://docs.github.com/en/github/working-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site (note, this guide is intended for jekyll sites)

## request re framework - not jekyll

If you use a framework to build a static site (like hugo), please don't use Jekyll. It's just been a PITA recently and I'd like us to diversify a bit

## notes

The distribution directory can be changed in settings (e.g. `_dist` or something). then you can just commit the built site to that dir. Maybe github actions could be used to build the site? I haven't looked in to github actions + github pages deployments.
