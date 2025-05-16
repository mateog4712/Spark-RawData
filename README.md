# Spark-RawData

#### Description:
This repository holds all of the data for the Spark project. There are three main folders: TimeAndMemory, CandidatesAndTraceArrows, and  ProofOfConcept. ProofOfConcept holds the all input and output files to show that Spark produces the same result as HFold given the same input. Alternative structures do exist -- as such, the energy was used as the metric for correctness. TimeAndMemory shows the comparison between Spark, RNAFold, and  HFold when observing time (s) and memory (KB).
CandidatesAndTraceArrows shows the number of V candidates and trace arrows produced by Spark when using the PK (standard) and PKfree option. As an additional comparison, we juxtapose it against a full quadratic matrix.