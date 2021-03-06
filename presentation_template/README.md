# Presentation template

This folder contains a template R Markdown document to generate a presentation with `xaringan`.

See this link for more information on the basics of it: https://slides.yihui.org/xaringan

This format is a slight modification of the basic "Ninja Presentation" template.

A `libs` folder will be created in the folder where you store your Rmd file - and will be accessed by the main html file that will be knitted out of it.

The xaringan package can be installed from CRAN:

https://cran.r-project.org/web/packages/xaringan/index.html

```
install.packages("xaringan")
```

## Getting started

- install `xaringan`
- copy over the entire content of the `presentation_template` folder as the folder where you are expected to store your presentation later - ideally rename it with the chapter number/title
- edit the Rmd file
- compile the presentation with `knitR` 
- that's it!

## Misc

Alternative formats can be found e.g. here: https://bookdown.org/yihui/rmarkdown/ioslides-presentation.html (yet this format is not anymore actively under development).

