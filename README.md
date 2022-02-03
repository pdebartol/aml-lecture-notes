# Advanced Machine Learning Lecture Notes Fall 2020

[@pierobartolo](https://github.com/pierobartolo) and [@MirkoDeVita98](https://github.com/MirkoDeVita98) co-authored these lectures notes for the Advanced Machine Learning course at ETH Zürich. [@lucidBrot](https://github.com/lucidBrot/) collected changes from their two repositories, as well as from [@advilema](https://github.com/advilema) and combined them in one repository.

**You have all the rights to fork this repository and build upon it as long as you give credits to the authors.**

## Access
To pull the notes to your local computer you must first `clone` the repository.
In the terminal, navigate to the root directory where you'd like the notes to
be located and enter:

    git clone https://github.com/pierobartolo/AML-Lecture-Notes
    cd AML-Lecture-Notes

You will see a series of `.tex` files in this folder, which are the latex
source files broken down by lecture. To read the files as a pdf, you must
compile them with the following command:

    pdflatex lecture_x

Once compiled, you should see `lecture_x.pdf`.

To build all the files at once, you can do (Windows Cygwin. I assume you'd know how to do this if you are on linux):

```
for i in *.tex; do /cygdrive/f/Programme/MiKTeX_20.11/miktex/bin/x64/pdflatex -halt-on-error -output-directory pdf "$i" ; done
```

