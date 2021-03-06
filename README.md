# Seq-view
Visualizing your Sequences on the Terminal with color

### Attention: biopython is prerequisite before you run this script

<a href="#quickStart">1. Quick Start</a>

<a href="#Aligned">2. Aligned fasta</a>

<a href="#fastq">3. Fastq</a>




## <a id="quickStart">Quick start</a>

Normal view:
```
Python3.7 Seq-view1.3 -i Example1.fa
```

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-1.png" width="350" title="hover text">
</p>


## Update
This script can automatically distinguish the fasta and fastq file by simply using the command above. And when all sequences in a fasta file share equal number of length, it can add '-a' automatically.



## <a id="Aligned">Aligned fasta</a>:
```
Python3.7 Seq-view1.3 -i Example2.fa
```

It will show like:
<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/image.png" width="600" title="hover text">
</p>

If you still want the colorful output, you can add a -c C like that:
```
Seq-view1.3 -i Example3.fq  -f fastq -r 1,2000  -a 200 -c C
```


Extra:

you can also print the Seq from 45 to 50:

```
Python3.7 Seq-view1.3 -i Example2.fa -r 45,50
#or
Python3.7 Seq-view1.3 -i Example2.fa  -r 4,5
```

You can also change the base number per line during the print when you print "aligned Seq":

```
Python3.7 Seq-view1.3 -i Example2.fa -a 200 -r 4,5
```



<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-5.png" width="600" title="hover text">
</p>

# <a id="fastq">For fastq visulization</a>

There have 3 functions for the fastq view:

1: print the fastq with Seq and scores (normal view): 

```
Seq-view1.2 -i Example3.fq  -f fastq -r 1,2000
```

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-8.png" width="600" title="hover text">
</p>


2: Print the aligned the sequences only, so that it is easy to show the adapter on the head or tail of the Seq:

```
Seq-view1.2 -i Example3.fq  -f fastq -r 1,2000  -a 200
```
<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-6.png" width="600" title="hover text">
</p>

3: Print the score of the Sequence only (So, you can view the score of the whole seq directly. and the score of the base which lower than 22 will be marked with the red background):

```
Seq-view1.2 -i Example3.fq  -f fastq -r 1,2000  -fq s
```

<p align="center">
  <img src="https://github.com/Karobben/Seq-vew/blob/master/Examples/Seq-7.png" width="600" title="hover text">
</p>



