# Ape repository

This repo has scripts used to make chigor.raf, a file in Legofit's
.raf format, which contains the chimpanzee and gorilla reference
sequences. The repo doesn't contain the data; just the scripts used to
generate the data.

The scripts used to download the original data are in subdirectories
`panTro5` and `gorGor5`. See the README.md files there for details.

## Make .raf file for common chimp reference sequence

    sbatch chimpraf.slr

## Make .raf file for gorilla reference sequence

    sbatch gorraf.slr

## Make .raf file for combined chimpanzee and gorilla

    sbatch chigor.slr
