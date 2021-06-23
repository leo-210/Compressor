
# 📁 Compressor

## Introduction

A little python program that [compresses data](https://en.wikipedia.org/wiki/Data_compression). Works better when there's more data. Decompression doesn't really work
on images, so it is best to try it with text files.

*Ps : if you want to compress a file for general purpose, don't use this, it is really not so inefficient lol.*

## Run the code

If you want to try it yourself, first make sure you have 
installed [python](https://www.python.org/downloads/) 3.7 or above. Then download the [compressor.py](src/compressor.py)
file.  
At this point, open a terminal, go to the folder where you 
have the python file with `cd "your/path"` and run
`python3 compressor.py "file/you want/to compress"` *use `py`or `python` if this doesn't work*.  
It will create two files : `compressed.cmprs` and `decompressed.idklol`

Note: The program writes the percentage of memory saved. If the percentage is negative, that means that the "compressed" file take more space than the not compressed one.

Have fun !

![banner](https://repository-images.githubusercontent.com/379695723/62e45b80-d47f-11eb-8b3e-0e17a4f93006)
