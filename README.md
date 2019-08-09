# pdfbooklet

## What is pdfbooklet?
A perl script that re-arranges the page order of a PDF file as a booklet.

## How to install pdfbooklet?
Install *perl* command first. On MacOS, perl must be re-installed.
On Linux, you can install perl with command as follows:

    $ sudo apt-get install perl  # on Ubuntu/Debian
    $ sudo yum install perl

Install the required perl packages by **cpan** command as follows:

    $ sudo cpan Gertopt::Long File::Basename File::Temp

Then, put *pdfbooklet* file in your command search path ($PATH), for example /usr/local/bin.

    $ sudo cp -p pdfbooklet /usr/local/bin/

## How to use pdfbooklet?
If you have a PDF file named *mypdf.pdf* and want to convert it to a booklet, run **pdfbooklet** as follows:

    $ pdfbooklet input.pdf

Then, you will have *input-booklet.pdf* file.

The following options are available:

* --output=*output.pdf*  to specify the name of output file.
* --twoup to put 2 pages onto one page (2up)

## What does pdfbooklet depend on?
In order to run it, the following commands/libraries are necessary.

* Commands
  + /usr/bin/perl (5.x)
  + /usr/local/bin/cpdf  (http://community.coherentpdf.com/)
* perl packages
  + Getopt::Long
  + File::Basename
  + File::Temp

## License?
This is a Public Domain Software.
