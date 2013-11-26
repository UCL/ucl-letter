UCL LaTeX Letter template
======================

by Simon Byrne

These files provide a letter template that is a close approximation to the
[UCL Corporate Identity](http://www.ucl.ac.uk/corporate-identity), using the
KOMA-Script letter class `scrlttr2`.


Installation
------------

To use once, simply put the files in the directory of your document.

A more permanent solution is to put the files somewhere in your texmf tree. To
find out where this is in your system, type the command:

    kpsewhich -var-value TEXMFHOME

An appropriate place would be `<texmf>/tex/latex/ucl-letter`


Use
----

See `sample.tex` for sample usage.

You will need to create your own personal *letter class option* (lco) file:
this contains details that you would want to keep consistent across letters,
such as your name, contact details, department and signature. See `sample.lco`
for an example.

For further details on the options, see the KOMA-Script documentation.

Support
-------

Requires a reasonably modern TeX installation (it has only been tested on MacTeX 2012). If you're having any problems,
try upgrading.

This is completely unofficial, and not supported by UCL. If you notice any
bugs however, contact simon.byrne@ucl.ac.uk, and I shall do my best to fix
them. Of course, any contributions are also welcome.
