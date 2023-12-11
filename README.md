# Enhancing-Privacy-in-Kmeans-through-Cluster-fusuion
Differential privacy has become a cornerstone in data
analysis, particularly in the realm of k-means clustering
algorithms. Existing approaches typically introduce a
uniform amount of noise to centroids during iterative
computations. In this paper, we present a novel
differentially private k-means clustering algorithm, DPKCCM. This algorithm enhances clustering utility by
incorporating adaptive noise and introducing a clustermerging strategy.
To achieve k clusters with differential privacy, DP-KCCM
initiates with n×k centroids, adds adaptive noise iteratively
to obtain n×k clusters, and subsequently merges these
clusters into k ones. Theoretical proofs validate the
differential privacy guarantees of our proposed algorithm.
Surprisingly, extensive experimental results reveal three
key findings: cluster merging with equal noise improves
utility to some extent; while adding adaptive noise alone
does not significantly enhance utility, combining cluster
merging and adaptive noise markedly improves utility; we
demonstrate the effectiveness of Gaussian noise in handling
datasets without outliers
