title: Cavity contour segmentation in chest radiographs using supervised learning and dynamic programming
authors: P. Maduskar, L. Hogeweg, P.A. de Jong, L. Peters-Bax, R. Dawson, H. Ayles, C.I. Sánchez and B. van Ginneken
has_pdf: True
template: publication
bibkey: madu14
published_in: Medical Physics
pub_details: <i>Medical Physics</i> 2014;41:071912-1 - 071912-15
doi: https://doi.org/10.1118/1.4881096
pmid: http://www.ncbi.nlm.nih.gov/pubmed/24989390
Efficacy of tuberculosis (TB) treatment is often monitored using chest radiography. Monitoring size of cavities in pulmonary tuberculosis is important as the size predicts severity of the disease and its persistence under therapy predicts relapse. The authors present a method for automatic cavity segmentation in chest radiographs.A two stage method is proposed to segment the cavity borders, given a user defined seed point close to the center of the cavity. First, a supervised learning approach is employed to train a pixel classifier using texture and radial features to identify the border pixels of the cavity. A likelihood value of belonging to the cavity border is assigned to each pixel by the classifier. The authors experimented with four different classifiers:k-nearest neighbor (kNN), linear discriminant analysis (LDA), GentleBoost (GB), and random forest (RF). Next, the constructed likelihood map was used as an input cost image in the polar transformed image space for dynamic programming to trace the optimal maximum cost path. This constructed path corresponds to the segmented cavity contour in image space.The method was evaluated on 100 chest radiographs (CXRs) containing 126 cavities. The reference segmentation was manually delineated by an experienced chest radiologist. An independent observer (a chest radiologist) also delineated all cavities to estimate interobserver variability. Jaccard overlap measure ÃŽÂ© was computed between the reference segmentation and the automatic segmentation; and between the reference segmentation and the independent observer's segmentation for all cavities. A median overlap ÃŽÂ© of 0.81 (0.76 Ã‚Â± 0.16), and 0.85 (0.82 Ã‚Â± 0.11) was achieved between the reference segmentation and the automatic segmentation, and between the segmentations by the two radiologists, respectively. The best reported mean contour distance and Hausdorff distance between the reference and the automatic segmentation were, respectively, 2.48 Ã‚Â± 2.19 and 8.32 Ã‚Â± 5.66 mm, whereas these distances were 1.66 Ã‚Â± 1.29 and 5.75 Ã‚Â± 4.88 mm between the segmentations by the reference reader and the independent observer, respectively. The automatic segmentations were also visually assessed by two trained CXR readers as "excellent," "adequate," or "insufficient." The readers had good agreement in assessing the cavity outlines and 84\% of the segmentations were rated as "excellent" or "adequate" by both readers.The proposed cavity segmentation technique produced results with a good degree of overlap with manual expert segmentations. The evaluation measures demonstrated that the results approached the results of the experienced chest radiologists, in terms of overlap measure and contour distance measures. Automatic cavity segmentation can be employed in TB clinics for treatment monitoring, especially in resource limited settings where radiologists are not available.
