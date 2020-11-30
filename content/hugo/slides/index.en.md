---
outputs:
- Reveal
title: Hugo & hugodown
hidden: true
layout: list
weight: 1
output: hugodown::md_document
countdown: true
rmd_hash: 6b1814a65f6c9f0a

---

Hugo and hugodown
=================

A powerful static generator, a handy WIP minimal package

------------------------------------------------------------------------

[Hugo](https://gohugo.io/)
==========================

Powerful and fast static generator

Only an .exe to install :tada:

------------------------------------------------------------------------

[hugodown](https://hugodown.r-lib.org/)
=======================================

[R :package:](https://hugodown.r-lib.org/)

-   An R Markdown output format

-   Handy helpers

Experimental but easier to start with in my opinion.

------------------------------------------------------------------------

From Rmd to website
===================

Under the hood

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |"R ( hugodown :package:, </br> downlit :package:) </br> & Pandoc"| B{md}
    B --> |"Hugo (Goldmark, Chroma)"| C[HTML]
{{< /mermaid >}}

<small>Inspired by [Emi Tanaka's post](https://emitanaka.org/r/posts/2018-12-12-scientific-and-technical-blogging-radix-vs-blogdown/)</small>

------------------------------------------------------------------------

From Rmd to website
===================

What you do

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |":large_blue_circle: knit button"| B{md}
    B --> |"hugo build (locally or cloud)"| C[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

No syntax highlighting :expressionless:

<pre><code>ggplot2::ggplot()
</code></pre>

Chroma syntax highlighting :+1:

```r
ggplot2::ggplot()
```

downlit syntax highlighting :smiley:

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'>ggplot2</span><span class='nf'>::</span><span class='nf'><a href='https://ggplot2.tidyverse.org/reference/ggplot.html'>ggplot</a></span><span class='o'>(</span><span class='o'>)</span>
</code></pre>

</div>

------------------------------------------------------------------------

{{< figure src="/images/highlight.jpg" alt="A meme to explain why downlit is great" height="550" >}}

Inspired by [Mara Averick](https://twitter.com/dataandme/status/1255510799273132032)

------------------------------------------------------------------------

hugodown syntax highlighting
============================

-   downlit for R :tada:

-   Chroma for other languages :sparkles:

------------------------------------------------------------------------

:mountain_cableway: Time for a demo!

[Notes on the course website](/hugo/demo/)

------------------------------------------------------------------------

Scientific Rmd Blog Checklist

-   [x] R Markdown
-   [x] Syntax highlighting
-   [x] Modern
-   [x] .bib
-   \[?\] Citation for posts (possible but custom layout)
-   [x] Equations

------------------------------------------------------------------------

Sustainability
==============

Created by:

<div class="highlight">

Hadley Wickham \[aut, cre\]

</div>

Used for [tidyverse.org](https://tidyverse.org), in particular.

[Active development](https://github.com/r-lib/hugodown/).

------------------------------------------------------------------------

Limitations?
============

-   hugodown is a WIP minimal package.

-   the function I demo-ed is in my fork, see the main project for existing theme.

-   Hugo changes a lot (but hugodown helps protect your projects from that)

------------------------------------------------------------------------

What about blogdown?!
=====================

It recently got updated so it can work like hugodown (no old post building, pfiew).

Many features! E.g. build.R and build2.R

The blogdown book will be updated soon

------------------------------------------------------------------------

So blogdown or hugodown
=======================

-   Start with hugodown, minimal and less docs to read.

-   Follow the RStudio blog to know about blogdown updates.

-   Switch to blogdown if you need a more custom workflow? Or after its book update?

------------------------------------------------------------------------

Further resources
=================

[Listed on the course website](/hugo/further-resources/) :ledger:

------------------------------------------------------------------------

Questions, comments?
====================

Write them in the chat!

------------------------------------------------------------------------

Time for a break :tea:
======================

<!--html_preserve-->

<div id="timer_hugo" class="countdown" style="top:100;left:0;" data-warnwhen="0">

<code class="countdown-time"><span class="countdown-digits minutes">05</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>

</div>

<!--/html_preserve-->

