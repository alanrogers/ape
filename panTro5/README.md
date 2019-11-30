# Alignment of common chimp reference sequence to hg19

Download alignments

    sbatch downloadpt5.slr

Select relevant portion of checksum file and check files.

    egrep "chr[0-9]+\.hg19" md5sum.txt > foo
    mv foo md5sum.txt
    md5sum -c md5sum.txt

All files are OK.

