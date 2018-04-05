# free-cv-templates-boostrap-v4
build your own cv for free with wkhtmltopdf

# install ubuntu 16.04
```
$ sudo apt update
$ sudo apt install wkhtmltopdf
```
https://wkhtmltopdf.org/downloads.html

# test
```
$ wkhtmltopdf http://www.google.com google.pdf
```

# build your own cv
```
$ cd free-cv-templates-boostrap-v4
$ wkhtmltopdf templates/cv-01-software-developer-template.html media/cv_full_name.pdf
```
