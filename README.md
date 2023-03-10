# PDF_to_text-

## Download and install
- Website: http://www.xpdfreader.com/download.html
```
wget https://dl.xpdfreader.com/xpdf-tools-linux-4.04.tar.gz
unzip xpdf-tools-linux-4.04.tar.gz
tar -xfv xpdf-tools-linux-4.04.tar.gz 
```

## Move all pdf's to the directory with 'pdftotext' file and run:

```
bash
for f in `ls *.pdf` ; do pdftotext -layout $f > ${f%.pdf}.txt ; done


```
