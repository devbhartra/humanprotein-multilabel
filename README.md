# humanprotein-multilabel
A PyTorch project to classify tens of thousands of microscopic images of Human Proteins, originally a part of a Kaggle competition

In this competition, I developed this model, capable of classifying mixed patterns of proteins in microscope images. Images visualizing proteins in cells are commonly used for biomedical research, and these cells could hold the key for the next breakthrough in medicine. However, thanks to advances in high-throughput microscopy, these images are generated at a far greater pace than what can be manually evaluated. Therefore, the need is greater than ever for automating biomedical image analysis to accelerate the understanding of human cells and disease.

This is a multilabel image classification problem, where each image can belong to several classes. The class labels are as follows:
0: 'Mitochondria',
1: 'Nuclear bodies',
2: 'Nucleoli',
3: 'Golgi apparatus',
4: 'Nucleoplasm',
5: 'Nucleoli fibrillar center',
6: 'Cytosol',
7: 'Plasma membrane',
8: 'Centrosome',
9: 'Nuclear speckles'
Acknowledgements

The data from the competition has been taken from the Human Protein Atlas Image Classification competition on Kaggle.

This solution was placed at rank 14 on the private leaderboard.
