## Fusion_prediction
Fusion prediction approach of dataset and pathological images 


# prepare
1. WSI_Score: Output from clam-model


  Reference: https://github.com/mahmoodlab/CLAM
3. clinicopathological features

 Combine these information and make a CSV file


# Random Forest (RF) Model
 Use RandomForest.ipynb
 
 When using the file please change csv_path and feature list


# Support Vector Machine (SVM) Model
 Use SVM.ipynb
 
 When using the file please change csv_path and feature list


RF and SVM methods use Grid search for the parametor
