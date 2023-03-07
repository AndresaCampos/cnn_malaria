# cnn_malaria

Convolution neural network-based machine learning model to predict whether the cell in the given picture is parasitized by the genus Plasmodium or not.

Malaria, a disease caused by protozoan parasites of the genus Plasmodium, is not only an acute life threat in many developing countries but also a significant burden on the healthcare system worldwide.  Prompt and effective diagnostic methods are essential for the management and control of malaria. However, traditional diagnosis techniques like staining thin and thick peripheral blood smears and rapid test methods like OptiMAL, ICT require labor and high-cost toolkits. Thus, the efficiency may be limited due to time consumption, cost-effectiveness, labor intensiveness, etc1.

 

In recent years, researchers have been developing automated screening methods with the help of machine learning methods. It has been proved that with the help of computer vision techniques, we can detect malaria based on the photo of blood cells2. Moreover, the performance of CNN-based models for malaria detection performs better and can be trained easily with the help of a pre-trained model3.

 

Please note that differ in the previously mentioned paper, all pictures in this dataset contain only a single cell (which makes the classification task easier). All pictures in the training set offered to you are labeled with either 1(parasitized) or 0(uninfected). 

 

References:

Tangpukdee N, Duangdee C, Wilairatana P, et al. Malaria diagnosis: a brief review[J]. The Korean journal of parasitology, 2009, 47(2): 93.
Das D K, Ghosh M, Pal M, et al. Machine learning approach for automated screening of malaria parasite using light microscopic images[J]. Micron, 2013, 45: 97-106.
Rajaraman S, Antani S K, Poostchi M, et al. Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images[J]. PeerJ, 2018, 6: e4568.