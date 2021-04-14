# Dissertation sections

This file contains the instructions to fill in each of the dissertation sections required by G+PS.

Their are named in order of appearance in the dissertation [following UBC G+PS](https://www.grad.ubc.ca/current-students/dissertation-thesis-preparation/structure-theses-dissertations). Note that there are missing sections within these (e.g., table of contents goes between Preface and Acknowledgements). These are embedded in the `main_thesis.Rmd` file and need no modification.

*Note:* Non of this individual sections are intended to *knit* independently. For that to happen, you will need to include the *LaTex* packages. For testing, I recommend you go to the `main_script.RMD` and set all chunks but the one you are testing to `eval = F`

# Sections

## `00_Cover.Rmd`

- *Mandatory*
- [G+PS Instructions](https://www.grad.ubc.ca/sites/default/files/doc/page/thesis_checklist_title_page.pdf)

This is the title page of the dissertation. Note that in some cases you will need to play around with the `\vspace{n}` variable to set the spaces. For example, if your title is very long, you might require to reduce the  `\vspace{8mm}` between the title and the "by" line to `\vspace{5mm}`.

## `01_Committee_form.Rmd`

- *Mandatory*

All sections within brackets of this form need to be filled. For example, the name of your supervisor goes within the brackets of `\noindent\underline{\makebox[6in][l]{Name of your Supervisor}` in line 30. Note that you might need to change, add or remove some of the titles (e.g, Supervisory Committee Member) depending on how many members you have. 

This is one of the Committee forms provided by G+PS. [Here are a couple of other examples](https://www.grad.ubc.ca/sites/default/files/doc/page/committee_page-doctoral_example.pdf). You can also download the form and include it as a PDF. In that case just set the `Committee_form` chunk in the `main_script.Rmd` to `eval = F` and add a chunk (or modify it) to include the PDF. See [this discussion](https://www.r-bloggers.com/join-split-and-compress-pdf-files-with-pdftools/) and [this other one](https://community.rstudio.com/t/appending-a-pre-existing-pdf-to-a-new-created-by-r-markdown/45641/6) for some instructions on how to include a PDF document into a Rmarkdown.

## `02_Abstract.Rmd`

- *Mandatory*

Use this document to write your abstract. Note that It needs to be 350 words.

## `03_Lay_abstract.Rmd`

- *Mandatory*

Use this document to write your abstract. Note that It needs to be 150 words.

## `04_Preface.Rmd`

- *Mandatory*
- [G+PS Instructions](https://www.grad.ubc.ca/sites/default/files/doc/page/thesis_sample_prefaces.pdf)

Use this document to write your preface

- Note this section will not render in word. 

## `05_Glossary.Rmd`

- *Optional*
If you do not have a glossary set the `glossary` chunk to `eval = F` in the `main_script.Rmd`

If you have a glossary, fill in the table. Note that the abbreviation and the definition need to be in the same level. For example, if the fifth line/item of the abbreviation list is *UBC*, then the fifth line/item of the definition must be *University of British Columbia*. At the end, the glossary will be printed in alphabetical order so, no need to worry about that!

*Note*: I know there are "cleaner" ways to include a glossary in a document using [LaTex](https://www.overleaf.com/learn/latex/Glossaries). However, I was not able to make it work. If some one wants to tackle this, be my guest!

## `06_Acknowledgements.Rmd`

- *Optional*

Use this document to write your Acknowledgements section

## `07_Dedication.Rmd`

- *Optional*

Use this document to write your Dedication. It will print the dedication centred to the middle of the page.

## `08_Introduction.Rmd`
- *Mandatory*

Use this document to write your dissertation's introduction. Note this file contains an example of how to reference figures. 

## `09_Conclusion.Rmd`
- *Mandatory*

Use this document to write your dissertation's conclusion.
