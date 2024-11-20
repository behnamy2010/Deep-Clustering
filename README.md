
# Deep Clustering for Travel Pattern Mining

This repository contains the implementation of the paper:  
**"An Ensemble of Deep Clustering Models With Autoencoders to Mine Travel Patterns From Smart Card Data"**  
Published in **IEEE Transactions on Intelligent Transportation Systems**.

### Authors
- **Sharon Saronian**
- **Behnam Yousefimehr**  
- **Mehdi Ghatee**  
- **Mohammad Mahdi Bejani**  

**DOI:** [10.1109/TITS.2024.3475295](https://ieeexplore.ieee.org/abstract/document/10720611)  

---

## Abstract
In recent research, clustering algorithms have been utilized to analyze smart card travel patterns. However, these methods often struggle due to the need for a predetermined number of clusters and the challenges posed by the curse of dimensionality. To address these issues and improve travel pattern recognition from smart-card transactions, a new framework has been proposed. This framework uses autoencoders to extract low-dimensional representations from transactions and an ensemble of deep clustering models to identify patterns. Additionally, it compares geodetic and network distances between stations for feature extraction. A key advantage of this approach is its ability to automatically determine the number of clusters and effectively mitigate overfitting using the Sharon index based on Rademacher complexity. When applied to the London metro smart card benchmark with more than 10,000 samples, the framework identified 7 clusters of travel patterns, compared to 3 clusters by baseline methods. Each cluster corresponds to a specific day of the week, uncovering distinct travel behaviors across the week. Furthermore, within each cluster, the framework detected three daily sub-patterns: morning peak, midday, and evening peak. This resulted in 21 unique travel patterns, allowing a detailed analysis of both weekday and weekend travel dynamics. These findings were validated using the Davies-Bouldin, Silhouette, and Calinski-Harabasz indices. The impact of the starting time for daily services has also been analyzed, showing that daily travel patterns are highly sensitive to this parameter.---

## Dependencies
Ensure you have the latest versions of the following libraries:
- **Python 3.8+**
- `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`
- `scikit-learn` (for clustering algorithms like KMeans, DBSCAN)
- `torch` and `torchvision` (for deep learning with PyTorch)

---

## Citation
If you use this repository, please cite our paper:
```bibtex
@ARTICLE{10720611,
  author={Saronian, Sharon and Yousefimehr, Behnam and Ghatee, Mehdi and Bejani, Mohammad Mahdi},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={An Ensemble of Deep Clustering Models With Autoencoders to Mine Travel Patterns From Smart Card Data}, 
  year={2024},
  pages={1-10},
  doi={10.1109/TITS.2024.3475295}
}
```

---

## Contact
For any inquiries or collaborations, please contact:  
**Behnam Yousefimehr**  
📧 [behnam.y2010@aut.ac.ir](mailto:behnam.y2010@aut.ac.ir)
