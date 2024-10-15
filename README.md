The full dataset we used is 45GB and can be found on the following link: https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation . Here is the example of 5 MRI scans.
I have included 5 example MRI scans.


Download a version of the pretrained weights here: https://www.kaggle.com/code/rastislav/3d-mri-brain-tumor-segmentation-u-net/input?select=model_per_class.h5
when doing so uncomment the lines:

# del conformal_cal_data 
# del cal_smx_scores
# del cal_gt_labels

to clear the variables to free up storage
