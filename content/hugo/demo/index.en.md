---
title: Notes from the demo
menuTitle: Demo
weight: 5
slides: true
output: hugodown::md_document
rmd_hash: 68854c9c82f4be2d

---

-   install the remotes package, `install.packages("remotes)`

-   install the hugodown package from my fork if you are brave, [`remotes::install_github("maelle/hugodown@vanilla")`](https://remotes.r-lib.org/reference/install_github.html)

-   [`hugodown::hugo_install('0.78.2')`](https://rdrr.io/pkg/hugodown/man/hugo_install.html)

-   [`hugodown::create_site_vanilla()`](https://rdrr.io/pkg/hugodown/man/create_site_vanilla.html). Be happy to see everything happening automatically :sparkles:

-   [`hugodown::hugo_start(render_to_disk = TRUE)`](https://rdrr.io/pkg/hugodown/man/hugo_start.html), open localhost in the browser.

-   Change homepage

-   [`hugodown::use_post("post/new-rmd-post")`](https://rdrr.io/pkg/hugodown/man/use_post.html), knit, see post.

-   say there will probably be other themes later. show [Hugo theme gallery](https://themes.gohugo.io/) and how I would choose themes.

-   add [Twitter metadata](https://gohugo.io/templates/internal/#twitter-cards)

-   tweak one CSS thing in custom.css

-   [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html), [`hugodown::use_netlify_toml()`](https://rdrr.io/pkg/hugodown/man/use_netlify_toml.html), go to Netlify interface.

-   add URL to config

