# easy-combine-pdfs
Simple utility to combine all PDF files in a folder. Created while getting my CS degree and having many class slides that would be more convenient to search in one file but there were no good free options for this functionality on Windows.

## Pre-Requisites 
**Operating system:** linux

**Packages:** pdfunite

**Build:** 
* a directory containing all PDF files to be combined into one
* each PDF file has file extension ".pdf"

## How To Use

Run the program from one directory above the one created to hold all PDF files.
### Folder structure
Example structure

```
|-- combine_all_pdfs
|-- my_pdf_folder/
|  |-- my_first_pdf.pdf
|  |-- my_second_pdf.pdf
|  |-- my_third_pdf.pdf
```

### Run the script

**paramter 1:** directory name

**paramter 2:** final file name


``` 
combine_all_pdfs my_pdf_folder all_the_pdfs.pdf
```

### Outcome
Expect the new PDF to be in the same directory as the others.


```
|-- combine_all_pdfs
|-- my_pdf_folder/
|  |-- my_first_pdf.pdf
|  |-- my_second_pdf.pdf
|  |-- my_third_pdf.pdf
|  |-- all_the_pdfs.pdf
```






