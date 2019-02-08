# Re-IDentification paper
List of paper in re-identification(re-ID) field.
The repository consists as following format:
## Category or Keyword
All paper are classified by their approaches.
- [published year, site] Subject of paper\
	Short description of paper (optional)
- ~~already read paper~~

## Survey
- [2016 arXiv] Person Re-identification: Past, Present and Future

## Hand-Craft
- [2015 ICCV] Person re-identification with correspondence structure learning\
	Extract Color histogram + SIFT from fixed size of pathces
- [2015 ICCV] Scalable person re-identification: A benchmark (*Market-1501*)\
	Extract color names descriptor for each local patch and aggregate them.
- [2012 BMVC] Person reidentification by attributes. (*VIPeR*)\
	15 binary attributes are trained by using color and texture features.
- [2012 ECCVw] Person re-identification: What features are important?\
	Discover pedestrian prototypes with common attributes.
- [2015 CVPR] Transferring a semantic representation for person re-identification and search\
	Learn attributes from fashion photography datasets.
- [2016 CVPR] Improving person re-identification via pose-aware multi-shot matching\
	Esitmate human pose for matching
- [2014 ECCV] Person re-identification by video ranking\
	Use spatial-temporal discriptors (HOG3D, GEI-Gait Energy Image, FEP-Flowenvergy Profile)

## Deep learning
- [2014 ICPR] Deep metric learning for person re-identification
- [2014 CVPR] Deepreid: Deep filter pairing neural network for person re-identification
- [2016 CVPR] Learning deep feature representations with domain guided dropout for person reidentification\
	Identification (Classification) mode instead of verification
- [2016 ECCV] Mars: A video benchmark for large-scale person re-identification\
	MARS benchmark dataset. 

## RNN
- [2016 ECCV] A siamese long short-term memory architecture for human re-identification\
	LSTM for re-ID
- [2016 ECCV] Gated siamese convolutional neural network architecture for human re-identification\
	LSTM with gating function to capture patterns of a pair of images.
- [2016 CVPR] Recurrent convolutional network for video-based person re-identification\
	Identification loss is adoptied. Verification model (Siamese network)
- [2016 ECCV] Person re-identification via recurrent feature aggregation\
	Hand-Crafted features are fed into LSTM. Identification model
- [2016 arXiv] Deep recurrent convolutional networks for video-based person re-identification: An end-to-end approach\
	GRU is used

## Attention Model
- [2016 arXiv] End-to-end comparative attention networks for person re-identification\
	Soft attention model + Siamese network

## GAN
- [2018 CVPR] Person Transfer GAN to Bridge Domain Gap for Person Re-Identification
- [2018 NIPS] FD-GAN Pose-guided Feature Distilling GAN for Robust Person Re-identification

## Reinforcement Learning
- [2018 CVPR] Multi-Shot Pedestrian Re-Identification via Sequential Decision Making

## Feature Learning
- [2017 CVPR] One-Shot Metric Learning for Person Re-Identification
- [2018 CVPR] Features for Multi-Target Multi-Camera Tracking and Re-Identification

## End-to-End Re-ID system
- [2016 arXiv] Person re-identification in the wild\
	PRW benchmark dataset
- [2016 arXiv] End-to-end deep learning for person search

## To be classified
- [2015 ICCV] Multi-Scale Learning for Low-Resolution Person Re-Identification
- [2016 CVPR] Similarity Learning With Spatial Constraints for Person Re-Identification
- [2017 ICCV] Multi-Scale Deep Learning Architectures for Person Re-Identification
- [2018 CVPR] Adversarially Occluded Samples for Person Re-Identification
- [2018 CVPR] Attention-Aware Compositional Network for Person Re-Identification
- [2018 CVPR] Eliminating Background-bias for Robust Person Re-identification
- [2018 CVPR] Person Re-Identification With Cascaded Pairwise Convolutions
- [2018 CVPRw] Re-Identification for Online Person Tracking by Modeling Space-Time Continuum