# Sito personale di Marita Dante

Sito personale di Marita Dante.
Tutti i diritti riservati.

## Collegamenti

* Sito: [maritadante.it](https://maritadante.it/)
* [Guida Markdown in italiano](https://informaticabrutta.it/markdown-guida/)

## TODOs

* markdown
  * transform as much as possible into markdown (starting with sections likely to be edited often) but also
  * transform static parts into html without code (even at compile time, it's just added complexity)
  * put all .md resources into a subdir named as the page
* cleanup css / javascript
  * separate my own css modifications from the original in a separate css loaded in combo
  * for every book page, add a page wide css selector to allow for finegrained styling
  * separate site.js parts necessary for each page
* improve rendering on mobile (use fluid for book divs, responsive breaks for sliders -- do I need a professional?)
* optimize placement on search console, debug analytics
* make local copy of .js resources?
* publish "Pensieri sulla strada" via [kindle publishing](https://kdp.amazon.com/en_US/help/topic/G202172740)

## Documentation

* [Github pages docs](https://help.github.com/en/github/working-with-github-pages)
* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Github flavored markdown](https://guides.github.com/features/mastering-markdown/)
* [Kramdown quickref](https://kramdown.gettalong.org/quickref.html)
* [Kramdown CSS examples](https://digitaldrummerj.me/styling-jekyll-markdown/)
* [Jekyll](https://jekyllrb.com/)
* [Jekyll Themes](http://jekyllthemes.org) ([portfolio](http://bogoli.github.io/-folio/), [prologue](https://chrisbobbe.github.io/jekyll-theme-prologue))
* [Liquid](https://shopify.github.io/liquid/)
* [Google fonts](https://fonts.google.com/)
* [Google search console](https://search.google.com/search-console?resource_id=sc-domain:maritadante.it)

## Local development

* Run: ```export PATH="$HOME/.gem/ruby/2.6.0/bin:$PATH"; jekyll serve -w```
* [Jekyll localhost](http://localhost:4000/)
