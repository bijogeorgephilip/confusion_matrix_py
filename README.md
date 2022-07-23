# confusion_matrix_py
This code is a part of a fire detection algorithm developed by Philip et. al. (2022), where the generated and reference fire maps are subjected to comparison. 

*   **Input Image 1:** From the reference shapefile input file, pixel value corresponding to given latitude and longitude is **read** (Step [7])

*   **Input Image 2:** From the input Landsat image, pixel value corresponding to given latitude and longitude is **extracted**   (Step [8])

* **Function:** Compares the values retrieved from Input Image 1 and Input Image 2 and generates confusion matrix, 
which is further used for accuracy assessments (not part of this code).

Note: 
*If you want to compare all the points between the two input images instead of certain points decided by (lat long), you can simply ignore the step where the extraction is performed, and directly read each single pixel value to dataframe.*


### **Disclaimer:** 

The below python  based program is intended for educational and informative use only and author(s) does not claim to be an authority. Certain parts of program and the logical  structure are based on multiple references and  author(s) claims no credit and accepts no responsibility for the  correctness, completeness or  quality of the information provided. 

**Bijo George Philip**

Date: 23.06.2022


