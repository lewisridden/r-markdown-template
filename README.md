## Current Version of my R Notebook Template

Compared to default:
- uses a custom LaTeX template which adds extra fields to the header (this fork localises terminology e.g. Unit as opposed to Module)
- adds multiprocessing via a local PSOCK cluster and closes it on finishing running, or via manual execution on the chunk to do so e.g. crashing on a chunk to avoid hanging threads
- adds common boilerplate e.g import chunk, field for exercises etc

- 
## Installing the Templates

If you want to trial these templates within R Markdown, you can install the templates directly:

```
# install.packages("devtools")
devtools::install_github("lewisridden/r-markdown-template")
```

This will install the package `MyTemplates`. Once installed, they will be available within the R Markdown templates as shown below:

![R Markdown templates](https://i.imgur.com/Cnlbhsm.png)




## Adapting the Templates

If you want to use the package as a base for your own template, you may want to fork the upstream repository. It will help to read [Chapter 17](https://bookdown.org/yihui/rmarkdown/document-templates.html#) and [Chapter 18](https://bookdown.org/yihui/rmarkdown/new-formats.html) of the upstream text to find out more about this.
