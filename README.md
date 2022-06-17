# Reco_WSSS
This is Yin Xu's work for WSSS


Before looking through the work, I recommend you to first read the following literature:
###

1. [Weakly Supervised Semantic Segmentation by Pixel-to-Prototype Contrast](https://arxiv.org/abs/2110.07110)

2. [Railroad is not a Train: Saliency as Pseudo-pxiel Supervision for Weakly Supervised Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_Railroad_Is_Not_a_Train_Saliency_As_Pseudo-Pixel_Supervision_for_CVPR_2021_paper.pdf)

3. [Weakly Supervised Learning of Instance Segmentation with Inter-pixel Relations](https://arxiv.org/abs/1904.05044)

###

Requirements:
* [Pascal Voc](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/)
* [Salience map](https://drive.google.com/file/d/19AjSmgdMlIZH4FXVZ5zjlUZcoZZCkwrI/view)

###

Steps of experiments:
* You can directly run the code by excuting the script script_contrast.sh on the script folder.
*  The steps consist of 
   *  Train the seeds
   * Post processing with CRF
   * Evaluation
