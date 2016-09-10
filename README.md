# Volksboard
Template and other support files for building a low-cost Steno keyboard

The `kbd*.ps` file contains a simple postscript program for generating
the Volksboard layout template. Rather than trying to print it directly
it seems better to generate a PDF file using `ps2pdf`:
```
ps2pdf kbd-18.5.ps
```
and print the resulting `kbd-18.5.pdf`

By the way, the 18.5 in the name refers to the vertical center-to-center
spacing of the switches. Both it and the horizontal spacing (currently 20mm)
are easily changed by changing constants at the top of the `.ps` file.

Instructions for building the board are in a [Google Doc](https://docs.google.com/document/d/1f9g5ClvySoVBOnJzF_X80j66RdHbnakePKb2xWS5gLM/edit?usp=sharing).

Firmware for the board is available on [GitHub](https://github.com/chauser/StenoFW)


