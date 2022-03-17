# Motif-Finding
In class we described the Gibbs sampling approach to motif finding. Implement the algorithm and apply it to the sequences provided as the fasta file associated with this assignment, available via Canvas. Run your algorithm and experiment with different motif lengths and other parameters of the algorithm. Do you obtain consistent results across different runs of your code? The data you were given is taken from ChIP-seq experiments for the transcription factor USF1. Compare the motif your found with the motif provided in the CIS-BP database and comment on the similarity. Note that the provided file contains a large number of sequences.
When developing your algorithm, test it first on a toy dataset that you create by embedding a motif in a small set of short sequences. Demonstrate that your algorithm indeed works on this small dataset.

The motif found by your Gibbs sampler should be returned as a list-of-lists, where each element in the list is a list of length four that corresponds to a position in the motif. For example, the list

[[1.0, 0, 0, 0], [0,1.0,0,0], [0,0,1.0,0],[0,0,0,1.0]]
corresponds to the motif ACGT.
