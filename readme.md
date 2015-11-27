Data for blog on sam and bam files


1. high quality pair x2
2. pair one low quality
3. high quality orphan

1. use bowtie
2. bam or sam?
3. show diff
4. use samtools to change
5. header

show what it looks like on igv

commmands 
#make a bowtie index
bowtie2-build reference.fa reference

#
bowtie [options]* <ebwt> {-1 <m1> -2 <m2> | --12 <r> | <s>} [<hit>]
bowtie reference -1 test_R1.fq -2 test_R2.fq > adh.sam

Warning: skipping mate #1 of read 'HWI-7001326F:39:C7N3UANXX:1:1101:10000:62296/1' because length (1) <= # seed mismatches (0)
Warning: skipping mate #1 of read 'HWI-7001326F:39:C7N3UANXX:1:1101:10000:62296/1' because it was < 2 characters long
4 reads; of these:
  4 (100.00%) were paired; of these:
    1 (25.00%) aligned concordantly 0 times
    3 (75.00%) aligned concordantly exactly 1 time
    0 (0.00%) aligned concordantly >1 times
    ----
    1 pairs aligned concordantly 0 times; of these:
      0 (0.00%) aligned discordantly 1 time
    ----
    1 pairs aligned 0 times concordantly or discordantly; of these:
      2 mates make up the pairs; of these:
        1 (50.00%) aligned 0 times
        1 (50.00%) aligned exactly 1 time
        0 (0.00%) aligned >1 times
87.50% overall alignment rate


