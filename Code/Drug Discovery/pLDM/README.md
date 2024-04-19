The following are modifications or improvements to original notebooks. Please refer to the authors' models for the published primary work.

Total Run Time: Protein language diffusion model pLDM.pt 4.14GB file takes minutes to load; with other installations
NVIDIA V100 High Ram GPU average of 8 protein generations = 10.71 seconds each 
NVIDIA A100 40GB GPU average of 8 protein generations = 8.87 seconds each 

Generative AI Cost Efficiency: NVIDIA V100 High Ram GPU average of 8 protein generations = 0.9528
Generative AI Cost Efficiency: NVIDIA A100 40GB GPU average of 8 protein generations = 0.4777
Equation: 1/(0.2 * Time average * Hourly gpu cost); V100 = 1/(0.2 * 10.71 * 0.49), A100 = 1/(0.2 * 8.87 * 1.18) 

Summary: Several minutes were needed for loading and installing packages prior to protein generations
V100 High Ram GPU for protein generations was $0.49/hr, only 20% slower, and twice as cost efficient
V100 is the better GPU choice for pLDM in many applications, Protein generation is practical for drug discovery 

ChemicalQDevice research & development of Ni, B., et al. 2024 Science Advances notebook
The number of generations based on highest pull forces was increased to eight proteins
Perplexity decreased with pulling force, likely associated with less alpha helix structural motifs
GPU Cost efficiency study highlighted appropriateness of NVIDIA V100 High Ram GPU, shown above