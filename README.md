# Seq-vew
View your Sequence on the Terminal with colour

### attatin: biopython is needed before you run the script

## Quick start

Normal view:
Python3.7 Seq-view1.0 -i Example.fa


<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Seq-1.png" width="350" title="hover text">
</p>


Aligned view:
Python3.7 Seq-view1.0 -i Example.fa -a 70

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Seq-3.png" width="350" title="hover text">
</p>


Extral:

you can also print the Seq from 45 to 50:
Python3.7 Seq-view1.0 -i Example.fa -r 45,50
or
Python3.7 Seq-view1.0 -i Example.fa -a 70 -r 45,50

You can also change the base number per line during the print when you print "aligned Seq":
Python3.7 Seq-view1.0 -i Example.fa -a 200 -r 45,50

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Seq-5.png" width="600" title="hover text">
</p>
