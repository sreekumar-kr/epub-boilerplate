ePub-Boilerplate
================

http://javierarce.github.com/epub-boilerplate

ePub Boilerplate is a simple template that helps you build ePub-formatted books.

## How to use it

1. Get the template:

        $ git clone git@github.com:javierarce/epub-boilerplate.git

2. Edit the contents of the **book** directory.

3. Run the publish script to generate and validate the book:

        $ ./publish book.epub

## ePub validation

This project uses epubcheck to validate the generated ePubs. If the build.sh script complains when running epubcheck, make sure you have java installed and it's in your PATH.

If you need help running epubcheck read this <a href="http://blog.threepress.org/2010/12/16/running-epubcheck-on-your-computer/">step-by-step guide</a>.

## Using the check script to validate the book.

    $ ./check book.epub
    
## Style

*Caveat lector*: currently there aren't any defined styles. While I add a basic layout have a look at the <a href="https://github.com/mattharrison/epub-css-starter-kit">ePub CSS Starter Kit</a>.

## Useful resources
      
* [EPUB 3.0 spec](http://idpf.org/epub/30)
* [Device compatibilty chart](http://wiki.mobileread.com/wiki/Device_Compatibility)
* [ePub CSS Starter Kit](https://github.com/mattharrison/epub-css-starter-kit)
* [ePub Validator](http://code.google.com/p/epubcheck)
* [UUID generator](http://www.famkruithof.net/uuid/uuidgen)
* [BISAC Subject Headings List](http://www.bisg.org/what-we-do-0-136-bisac-subject-headings-list-major-subjects.php)
* [Practical ePub metadata: Authorship](http://blog.threepress.org/2009/11/27/practical-epub-metadata-authorship/)
* [MARC Code List for Relators](http://www.loc.gov/marc/relators)
* [What Is EPUB 3? An Introduction to the EPUB Specification for Multimedia Publishing](http://shop.oreilly.com/product/0636920022442.do)
