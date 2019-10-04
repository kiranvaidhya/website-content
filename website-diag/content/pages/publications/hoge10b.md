title: Evaluation of a computer aided detection system for tuberculosis on chest radiographs in a high-burden setting
authors: L. Hogeweg, C. Mol, P.A. de Jong, H. Ayles, R. Dawson and B. van Ginneken
has_pdf: False
template: publication
bibkey: hoge10b
published_in: Annual Meeting of the Radiological Society of North America
pub_details: in: <i>Annual Meeting of the Radiological Society of North America</i>, 2010
PURPOSE : In high tuberculosis (TB) burden regions the use of chest radiographs (CXR) to detect TB is limited by the low number of skilled readers available. The performance of a computer aided diagnosis (CADx) system to detect TB on CXR is evaluated. METHOD AND MATERIALS: The CADx system was designed to detect diffuse abnormalities and lung shape distortions. Unobscured lung fields were first segmented using pixel classification. For diffuse abnormality detection multiple small circular image patches were sampled inside the lung fields. Features based on moments of Gaussian derivatives and position in the lung field were calculated to classify the patches as normal/abnormal using a k nearest neighbor classifier. The probabilistic labels of the classified patches were combined using a quantile rule to assign one probability of abnormality to the image. To detect shape distortions, a shape representation was extracted from the lung field segmentation based on the distance of boundary points to the lung field centroid. A normal lung field shape model was created from training images using principal component analysis (PCA). A large Mahalanobis distance of an image to the PCA model indicates a high probability of being abnormal. The probabilities from the textural system and the shape system were averaged to obtain a final probability of being abnormal. The training set consisted of 216 digital CXRs (OdelcaDR, Delft Diagnostic Imaging, The Netherlands, 0.25 mm pixel spacing) from an outpatient clinic in Cape Town, South Africa in which abnormal regions were manually indicated by a radiologist. The test set consisted of 209 digital CXRs from a high TB burden outpatient clinic in Kanyama, Zambia, and had 66 normal and 143 abnormal cases. This reference standard was set by a radiologist. CADx was evaluated with Az, the area under the Receiver Operator Characteristic curve. RESULTS: Az of the CADx system was 0.81. Az for the textural abnormality detection system and the shape distortion system alone was 0.77, and 0.80, respectively. CONCLUSION : CADx is a promising tool for the detection of tuberculosis, and could improve TB case detection in high-burden regions. CLINICAL RELEVANCE/APPLICATION: The use of CADx for CXR could help to improve TB case detection rate in high-burden regions where resources and number of skilled readers are low.
