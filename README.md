# apache_fop_demo
Using Apache Fop to generate a PDF from an XML document and XSLT transform.

Based on the example at: http://blog.jaumesola.com/how-to-create-pdf-files-from-xml

FOP Version 1.1

#### Instructions

1) Install Apache Fop

2) Run

    $ fop -xml persons.xml -xsl transform.xsl -pdf document.pdf
