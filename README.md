# JODConverter

JODConverter (for Java OpenDocument Converter) automates document conversions
using LibreOffice or OpenOffice.org.

### Warning: This Repository is Unmaintained

I started this project back in 2003, and stopped maintaining it in 2012. I moved the code here at GitHub in the
hope that a well-maintained fork will emerge.

So you may want to use one of the more recently updated [forks](https://github.com/mirkonasato/jodconverter/network)
instead of this repository. Please don't bother submitting pull requests to this repository as they will simply be ignored.

The previous home for this project is at [Google Code](http://code.google.com/p/jodconverter/),
including some [wiki pages](https://code.google.com/archive/p/jodconverter/wikis).

-- Mirko Nasato

# About this Fork

I encountered a problem where documents would not be rendered in the correct locale.
Unfortunately it seems to me that there is no way to pass environment variables to the process creation,
thus I had to fork this and add the method "addEnvironmentVariable" into "DefaultOfficeManagerConfiguration".

This allows to add environment variables to the ProcessBuilder.

Thanks to VilleRoy from the Apache OpenOffice forums who helped me find the bug.
Source: [forum.openoffice.org](https://forum.openoffice.org/en/forum/viewtopic.php?f=6&t=93486)

-- Pavel Pipovic

