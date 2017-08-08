#SEQUENCE CLEANER
Description

Analyzing poor data takes CPU time and interpreting the results from poor data takes people time, so it's always important to make a pre-processing.

Let me call my script as “Sequence_cleaner” and the big idea is to remove duplicate sequences, remove too short sequences ( the user defines 
the minimum length) and remove sequences which have too many unknown nucleotides (N) ( the user defines the % of N is allows ) 
and in the end the user can choose if he/she wants to have a file as output or print the result.

Forked cdoorenweerd version: disabled appending taxon names to duplicate haplotypes taxonnames to prevent problems with very large numbers of duplicates and taxonnames becoming too long. Added the number of instances a haplotype was in the source fasta after the taxon name in the output.

