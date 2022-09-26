# Teaching CV

This CV version is used to apply for private tutoring positions.

## Build

Build the PDF file with:

```bash
docker run --rm \
  -v $(pwd):/workdir \
  -u $(id -u):$(id -g) \
  csegarragonz/latex-docker:0.1.2 SegarraCarlos_CV.tex
```
