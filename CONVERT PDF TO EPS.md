## How to conver from PDF to EPS
## Crop PDF file 

```
$ pdfcrop "file_name.pdf" "F1-temp.pdf"
```
## Convert to PS file
```
$ pdftops F1-temp.pdf F1.ps
```
* To use pdftops, poppler must be installed by BREW
```
$ brew install poppler
```

## Convert from PS to EPS file (If needed)
```
$ ps2eps F1.ps
```

