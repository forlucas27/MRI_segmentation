# MRI_segmentation

This program was created as an assignment for an online course. A neural network is built to 
automatically segment tumor regions in the brain using Magnetic Resonance Imaging (MRI)
scans. 

The MRI data is first processed where sub-volumes are created and standardized to have a mean 
of zero and a standard deviation of one. A model with a3D U-Net structure is built. The Soft Dice
loss function is used for training. The model is trained on BraTS data in the NifTI-1 format and 
finally evaluated using per-pixel sensitivity and specificity.
