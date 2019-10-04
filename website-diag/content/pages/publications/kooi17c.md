title: Discriminating solitary cysts from soft tissue lesions in mammography using a pretrained deep convolutional neural network
authors: T. Kooi, B. van Ginneken, N. Karssemeijer and A. den Heeten
has_pdf: True
template: publication
bibkey: kooi17c
published_in: Medical Physics
pub_details: <i>Medical Physics</i> 2017;44:1017-1027
doi: https://doi.org/10.1002/mp.12110
pmid: http://www.ncbi.nlm.nih.gov/pubmed/28094850
It is estimated that 7% of women in the western world will develop palpable breast cysts in their lifetime. Even though cysts have been correlated with risk of developing breast cancer, many of them are benign and do not require follow-up. We develop a method to discriminate benign solitary cysts from malignant masses in digital mammography. We think a system like this can have merit in the clinic as a decision aid or complementary to specialized modalities. We employ a deep convolutional neural network (CNN) to classify cyst and mass patches. Deep CNNs have been shown to be powerful classifiers, but need a large amount of training data for which medical problems are often difficult to come by. The key contribution of this paper is that we show good performance can be obtained on a small dataset by pretraining the network on a large dataset of a related task. We subsequently investigate the following: (a) when a mammographic exam is performed, two different views of the same breast are recorded. We investigate the merit of combining the output of the classifier from these two views. (b) We evaluate the importance of the resolution of the patches fed to the network. (c) A method dubbed tissue augmentation is subsequently employed, where we extract normal tissue from normal patches and superimpose this onto the actual samples aiming for a classifier invariant to occluding tissue. (d) We combine the representation extracted using the deep CNN with our previously developed features. We show that using the proposed deep learning method, an area under the ROC curve (AUC) value of 0.80 can be obtained on a set of benign solitary cysts and malignant mass findings recalled in screening. We find that it works significantly better than our previously developed approach by comparing the AUC of the ROC using bootstrapping. By combining views, the results can be further improved, though this difference was not found to be significant. We find no significant difference between using a resolution of 100 versus 200 micron. The proposed tissue augmentations give a small improvement in performance, but this improvement was also not found to be significant. The final system obtained an AUC of 0.80 with 95% confidence interval [0.78, 0.83], calculated using bootstrapping. The system works best for lesions larger than 27 mm where it obtains an AUC value of 0.87. We have presented a computer-aided diagnosis (CADx) method to discriminate cysts from solid lesion in mammography using features from a deep CNN trained on a large set of mass candidates, obtaining an AUC of 0.80 on a set of diagnostic exams recalled from screening. We believe the system shows great potential and comes close to the performance of recently developed spectral mammography. We think the system can be further improved when more data and computational power becomes available.
