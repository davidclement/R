## myknit.R
wraps knitr to make it easy-ish to use w/out using R Studio
- `myknitHTML` outputs HTML
- `myknitPDF` outputs PDF
- requires pandoc to be installed on the system http://johnmacfarlane.net/pandoc
- uses a system call to pandoc instead of via R b/c of hassles encountered w/ knitr's pandoc function
