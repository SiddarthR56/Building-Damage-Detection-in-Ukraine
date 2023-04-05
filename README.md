# Building-Damage-Detection-in-Ukraine
Predict the level of infrastructure damage in Ukraine using geospatial images and transfer learning techniques.


### Methodology

A two pronged approach was use to address image segmentation and classification. 

### Data 

To utilize with XView2 Data, please place the unzipped folder "train", "test", and "hold" within the data directory. This zips can be downloaded from the [xview challenge](https://xview2.org/download-links); the files of interest are the "Challenge training/holdout/test sets". 

### Expected Repo File Structure 


| data      
----| classification_images      
----| holdout_images     
----| testing_images     
----| train    
--------| images     
--------| labels     
--------| targets     
----| test     
--------| images    
--------| labels   
--------| targets     
----| mariupol_explore.ipynb     
----| preprocessing_classification_data.ipynb      
----| sentinel.ipynb     
----| visualize_data.ipynb    
| src     
----| cnn.ipynb 
----| segmentation.ipynb

  