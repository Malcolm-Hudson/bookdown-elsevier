# bookdown-elsevier

## Highlights

- Write academic papers of Elsevier journals with R markdown syntax.
- A live example is provided. I published it TODAY!
- Create multiple file formats, including .pdf, single .html, gitbook, .md, .epub, docx.

## Introduction

It is today that one of my academic manuscripts is published on *Agricultural and Forest Meteorology*, one of the top journals in my scientific research area. This paper is the first paper of mine written in R bookdown environment from the preparation to the publication. Hooray! Now it is time to share its bookdown files.

Elsevier is one of the world's major providers of scientific, technical, and medical information. Elsevier owns  2500 journals, which is why I would like to share my bookdown manuscript for re-use.

## An Example with Its Repo

The example is the paper I have just published TODAY. It is open-access. Users could either see it [online](https://www.sciencedirect.com/science/article/pii/S0168192318302880) or download the [pdf version](https://www.sciencedirect.com/science/article/pii/S0168192318302880/pdfft?md5=468fc112db3ae34ee56c2bfc1e802739&pid=1-s2.0-S0168192318302880-main.pdf). Before the publication, a version with numbered lines is recommended for reviewers, which looks like this:

![](https://github.com/pzhaonet/bookdown-elsevier/raw/master/showcase/elsevier_01.png)

![](https://github.com/pzhaonet/bookdown-elsevier/raw/master/showcase/elsevier_02.png)



![](https://github.com/pzhaonet/bookdown-elsevier/raw/master/showcase/elsevier_05.png)



![](https://github.com/pzhaonet/bookdown-elsevier/raw/master/showcase/elsevier_08.png)



![](https://github.com/pzhaonet/bookdown-elsevier/raw/master/showcase/elsevier_23.png)



It is produced by my bookdown project, which is available on the [GitHub Repo](https://github.com/pzhaonet/bookdown-elsevier). You could view the .docx, .epub, .html, .pdf, and .tex as well.

I should mention that you will fail in creating the book if you only download the repo and build it with R bookdown. You could see that in 'index.Rmd' there is a line which calls an R script:

```
source('scripts/paper.R')
```

paper.R processes my data and creates the data and figures for the manuscript. I would not like to share paper.R at the moment. Anyway, you could get an impression how the pdf is created from the .Rmd files even without seeing paper.R.

## Technical details

Elsevier provides a [LaTeX template](https://www.elsevier.com/authors/author-schemas/latex-instructions) which is free for using. I modified it as 'tex/template.tex', i.e. something was moved from the original LaTeX template to the yaml of 'index.Rmd'. Users could simply compare them and then get an idea how to convert a LaTeX template into a bookdown template.

## Re-use

- Download the [GitHub Repo](https://github.com/pzhaonet/bookdown-elsevier).
- Revise 'index.Rmd' as your own manuscript.
- Build the book with R bookdown.


Any suggestions are welcome. Just PR the repo!
