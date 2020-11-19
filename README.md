# COLAB_UPSNet
Running UPSNet on google colab.
Following is the description:
1. UPSNet_Colab_GDrive_DataSet.ipynb - To test and train the UPSNet, keeping cityscapes dataset on GDrive.
2. UPSNet_Colab_Local_DataSet.ipynb - To test and train the UPSNet, keeping cityscapes dataset in colab space.
3. TrainedModel - Contains trained model files, which can be used directly for testing purposes. These files need to be placed in the output folder at the location: output\upsnet\cityscapes\upsnet_resnet50_cityscapes_4gpu\train.
4. output - This folder contains the output of the test. 
5. Changed_Files - This folder included the changed files; required to train and test the UPSNet using the above-mentioned notebooks.

Train: For training space on google colab is less and also colab's session last for 8-12 hour; so we need to save the snapshot and next time start training from this snapshot onwards.
Test: For directly testing upload this output folder in UPSNet code and remove val directory from output\upsnet\cityscapes\upsnet_resnet50_cityscapes_4gpu. This directory will be generated after the test.

Note* To work with the above-mentioned notebooks change the files available in Changed_Files at appropriate places in UPSNet code.
