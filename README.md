# ocr-to-iptc

Jupyter notebook script to run OCR (using [Tesseract OCR](https://opensource.google/projects/tesseract)) then save the results to the image's [IPTC Caption](https://iptc.org/standards/photo-metadata/iptc-standard/).

## Prerequisites

[Jupyter Notebook](https://jupyter.org/) or alternative

[Tesseract OCR](https://opensource.google/projects/tesseract) - don't forget to update the path to the Tesseract executable in the notebook.

## Getting Started

> you may need to install missing python libraries, notable ones:
> - pytesseract
> - iptcinfo3
> - tqdm

1. Put images you want to process in the `./src` folder
1. Run the notebook
1. Review saved images in `./output`

## Miscellaneous

You can use `./samples` for some test images.
