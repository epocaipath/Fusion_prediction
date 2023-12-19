## Fusion_prediction
Fusion prediction approach of dataset and pathological images 


# prepare
1. WSI_Score: Output from clam-model

  Reference: https://github.com/mahmoodlab/CLAM

2. clinicopathological features

 Combine these information and make a CSV file


# Random Forest (RF) Model
 Use RandomForest.ipynb
 
 When using the file please change csv_path and feature list


# Support Vector Machine (SVM) Model
 Use SVM.ipynb
 
 When using the file please change csv_path and feature list


RF and SVM methods use Grid search for the parametor



## License
This code is made available under the GPLv3 License and is available for non-commercial academic purposes.

## Reference
This Github is modified from the codes at https://github.com/ayukat1016/gan_sample
