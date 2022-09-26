# Short CV (Public)

This CV version is a one-page CV ready to be disseminated publicly. Its main
traits are:
* No `Under Review` submissions
* No phone number
* Just one page

## Build

Build the PDF file with:

```bash
docker run --rm \
  -v $(pwd):/workdir \
  -u $(id -u):$(id -g) \
  csegarragonz/latex-docker:0.1.2 SegarraCarlos_CV.tex
```
