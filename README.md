# HGSleepNet: Multi-Scale Hypergraph Prototype Learning for Interpretable Sleep Staging
Anonymous Authors

# Abstract
Sleep staging is crucial for the diagnosis and intervention of sleep disorders. Although previous work has achieved significant progress, there are still urgent challenges: (1) How to model high-order functional connectivity in brain networks. (2) How to overcome significant inter-subject variability to improve model generalization. (3) How to provide an interpretable brain network to support clinical analysis. To address these challenges, we propose HGSleepNet, an innovative framework based on multi-scale hypergraph prototype learning. Specifically, we first design an adaptive hypergraph construction module that learns optimal functional connectivity patterns end-to-end while integrating a spatial proximity hypergraph to incorporate anatomical constraints. Secondly, we introduce a multi-scale prototype learning module that learns prototype representations of sleep stages at three levels: node, graph structure, and global. Finally, we achieve cross-subject feature invariance through a prototype alignment strategy. Experiments conducted on three sleep datasets demonstrate that HGSleepNet outperforms state-of-the-art baseline methods. Visualization results of the model further confirm its effectiveness in capturing high-order brain functional connectivity patterns across different sleep stages.

# Experimental Example
We provide the data processing, model architecture, parameter settings, training, and testing code on the **MASS-SS3** dataset. The dataset can be obtained upon request at [MASS](https://ceams-carsm.ca/mass/). We used a total of 2 EOG, 20 EEG, and 3 EMG signals from the **MASS-SS3** dataset.

This paper also conducted comprehensive experiments on two public datasets, **ISRUC-S1** and **ISRUC-S3**. The datasets can be obtained at [ISRUC](https://sleeptight.isr.uc.pt/).

# Citation

# Contact
If you have any detailed questions or suggestions, you can email us:
