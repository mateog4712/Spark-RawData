# Spark-RawData

#### Description:
This repository holds all of the data for the Spark project. There are four main folders: TimeAndMemory, CandidatesAndTraceArrows, Constraint, and  ProofOfConcept. 

ProofOfConcept holds the all input and output files to show that Spark produces the same result as HFold given the same input. Alternative structures do exist -- as such, the energy was used as the metric for correctness. 

TimeAndMemory shows the comparison between Spark, RNAFold, and  HFold when observing time (s) and memory (KB).

CandidatesAndTraceArrows shows the number of V candidates and trace arrows produced by Spark when using the PK (standard) and PKfree option. As an additional comparison, we juxtapose it against a full quadratic matrix.

Constraint shows the effect of input constraints on time and memory of Spark. We looked at sequences of length 1000, 5000, and 10000. For each length we generated 100 sequences by taking 4 bases sequences and producing 24 dinucleotide shuffled versions for each. For each sequence, we then generated multiple constraint structures for a total of 2200 sequence-structure combinations for each length.