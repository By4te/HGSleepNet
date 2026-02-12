# HGSleepNet: Multi-Scale Hypergraph Prototype Learning for Interpretable Sleep Staging
Anonymous Authors

# Abstract
Sleep staging is crucial for the diagnosis and intervention of sleep disorders. Although previous work has achieved significant progress, there are still urgent challenges: (1) How to model high-order functional connectivity in brain networks. (2) How to overcome significant inter-subject variability to improve model generalization. (3) How to provide an interpretable brain network to support clinical analysis. To address these challenges, we propose HGSleepNet, an innovative framework based on multi-scale hypergraph prototype learning. Specifically, we first design an adaptive hypergraph construction module that learns optimal functional connectivity patterns end-to-end while integrating a spatial proximity hypergraph to incorporate anatomical constraints. Secondly, we introduce a multi-scale prototype learning module that learns prototype representations of sleep stages at three levels: node, graph structure, and global. Finally, we achieve cross-subject feature invariance through a prototype alignment strategy. Experiments conducted on three sleep datasets demonstrate that HGSleepNet outperforms state-of-the-art baseline methods. Visualization results of the model further confirm its effectiveness in capturing high-order brain functional connectivity patterns across different sleep stages.

# Experimental Example
We provide the data processing, model architecture, parameter settings, training, and testing code on the **MASS-SS3** dataset. The dataset can be obtained upon request at [MASS](https://ceams-carsm.ca/mass/). We used a total of 2 EOG, 20 EEG, and 3 EMG signals from the **MASS-SS3** dataset.

This paper also conducted comprehensive experiments on two public datasets, **ISRUC-S1** and **ISRUC-S3**. The datasets can be obtained at [ISRUC](https://sleeptight.isr.uc.pt/).

# Experimental results
## Performance Comparison Across Datasets and Methods
We compared CNN-based method [DeepSleepNet](https://ieeexplore.ieee.org/abstract/document/7961240), RNN-based method [SeqSleepnet](https://ieeexplore.ieee.org/abstract/document/8631195), and graph-based methods [GraphSleepNet](https://www.ijcai.org/Proceedings/2020/184), [MSTGCN](https://ieeexplore.ieee.org/document/9530406), [FC-STGNN](https://ojs.aaai.org/index.php/AAAI/article/view/29500), [ST-USleepNet](https://www.ijcai.org/proceedings/2025/0466.pdf) on multiple public datasets.
<img width="665" height="285" alt="image" src="https://github.com/user-attachments/assets/29e57e6e-23f1-464a-946e-19be66e90147" />

## Ablation Study
We designed three variant models to validate the importance of each functional module. See the raw paper for detailed settings.
<img width="765" height="289" alt="image" src="https://github.com/user-attachments/assets/b0bf487e-981c-4847-8136-3a7955bc4718" />

## Visualization 
We provide a visual analysis of dominant hyperedges and node-level prototypes across different sleep stages to offer interpretability for the sleep staging model.
<img width="987" height="320" alt="image" src="https://github.com/user-attachments/assets/1af8a58a-5750-483a-b141-9b727b2a6809" />
<img width="974" height="358" alt="image" src="https://github.com/user-attachments/assets/6828e4e1-ffa2-4a1e-aaad-c9dd8e88e728" />

# Citation

# Contact
If you have any detailed questions or suggestions, you can email us:
