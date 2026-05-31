# ENGG2112-Project-Code
This repositry includes the main code used for the completion of Group 5's Predictive Engine Maintenance Project.


combined_cmapss_ml.ipynb represents the finalised code combining all ML approaches on the CMAPSS FD001 dataset. The same preprocessing was applied in the notebook for all approaches. Ultimately the GNB and RF results are presented in the report.

gnb_combined_dataset_5.ipynb represents the attempt to combine the CMAPSS data and the engine fault detection data into a single approach. This ultimately did not work. Particularly, the correlation heatmap output shows the main issue --> little to no correlation between features in the engine fault detection dataset. Final results --> barely better than a random classifier with 51% accuracy
