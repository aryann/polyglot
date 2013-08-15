polyglot
=======

This is my attempt at writing a program that is valid in multiple
languages:

    $ sh polyglot
    I am a Shell script!
    $ python polyglot
    I am a Python program!
    $ gcc -Wall -x c -o polyglot.out polyglot && ./polyglot.out && rm polyglot.out
    I am a C program!

As time passes, I will add support for additional languages.
