# Seq-view
View your Sequence on the Terminal with color

### Attention: biopython is needed before you run the script

## Quick start

Normal view:

Python3.7 Seq-view1.0 -i Example1.fa


<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-1.png" width="350" title="hover text">
</p>


Aligned view:

Python3.7 Seq-view1.0 -i Example2.fa -a 70

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-3.png" width="350" title="hover text">
</p>


Extra:

you can also print the Seq from 45 to 50:

Python3.7 Seq-view1.0 -i Example2.fa -r 45,50

or

Python3.7 Seq-view1.0 -i Example2.fa -a 70 -r 4,5


You can also change the base number per line during the print when you print "aligned Seq":

Python3.7 Seq-view1.0 -i Example2.fa -a 200 -r 4,5




<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-5.png" width="600" title="hover text">
</p>

# For fastq viewer

There have 3 function for fastq view:

1: print the fastq with Seq and scores (normal view): 

Seq-view1.2 -i Example3.fastq  -f fastq -r 1,2000

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-6.png" width="600" title="hover text">
</p>


2: Print the aligned the sequences only, so that it is easy to show the adapter on the head or tail of the Seq:

Seq-view1.2 -i ERS011978_pass_1.fastq  -f fastq -r 1,2000  -a 200

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-8.png" width="600" title="hover text">
</p>

3: Print the score of the Sequence only (So, you can view the score of the whole seq derectaly. and the score of the base which lower than 22 will be marked with the red background):

Seq-view1.2 -i ERS011978_pass_1.fastq  -f fastq -r 1,2000  -fq s

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-7.png" width="600" title="hover text">
</p>
