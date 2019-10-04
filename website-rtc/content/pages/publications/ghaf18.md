title: Student Beats the Teacher: Deep Neural Networks for Lateral Ventricles Segmentation in Brain MR
authors: M. Ghafoorian, J. Teuwen, R. Manniesing, F. de Leeuw, B. van Ginneken, N. Karssemeijer and B. Platel
has_pdf: True
template: publication
bibkey: ghaf18
published_in: Medical Imaging
pub_details: in: <i>Medical Imaging</i>, 2018, pages 105742U
doi: https://doi.org/10.1117/12.2293569
arxiv: https://arxiv.org/abs/1801.05040
Ventricular volume and its progression are known to be linked to several brain diseases such as dementia and schizophrenia. Therefore accurate measurement of ventricle volume is vital for longitudinal studies on these disorders, making automated ventricle segmentation algorithms desirable. In the past few years, deep neural networks have shown to outperform the classical models in many imaging domains. However, the success of deep networks is dependent on manually labeled data sets, which are expensive to acquire especially for higher dimensional data in the medical domain. In this work, we show that deep neural networks can be trained on muchcheaper-to-acquire pseudo-labels (e.g., generated by other automated less accurate methods) and still produce more accurate segmentations compared to the quality of the labels. To show this, we use noisy segmentation labels generated by a conventional region growing algorithm to train a deep network for lateral ventricle segmentation. Then on a large manually annotated test set, we show that the network significantly outperforms the conventional region growing algorithm which was used to produce the training labels for the network. Our experiments report a Dice Similarity Coefficient (DSC) of 0.874 for the trained network compared to 0.754 for the conventional region growing algorithm (p < 0.001).
