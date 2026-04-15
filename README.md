# Best practice guide for Bristol Uni users of OpenSAFELY

Rendered at [https://grpehr.github.io/os-bristol-best-practice/](https://grpehr.github.io/os-bristol-best-practice/)

This github is currently being updated

***

To build/render the html output open the project in RStudio and either

open the *Build* pane click the *Render Website* button

or 

run in R

```r
# install.packages('quarto')
quarto::quarto_render()
```

or 

at the command line

```bash
quarto render
```

or 

in Visual Studio Code by installing the Quarto extention

***

When editing the project, preview with

```r
quarto::quarto_preview()
```

or

Clicking the preview button in the top right of Visual Studio Code (or using the `ctrl+shift+k` shortcut)

or 

```bash
quarto preview
```
And stop the process with <kbd>Ctrl</kbd>+<kbd>C</kbd> or with

```r
quarto::quarto_preview_stop()
```
