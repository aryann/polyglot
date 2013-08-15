polygot
=======

This is my attempt at writing a program that is valid in multiple
languages:

    $ sh polygot
    I am a Shell script!
    $ python polygot
    I am a Python program!
    $ gcc -Wall -x c -o polygot.out polygot && ./polygot.out && rm polygot.out
    I am a C program!

As time passes, I will add support for additional languages.
