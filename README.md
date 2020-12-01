# IBM-Advanced-Data-Science-Capstone-master







Frist of all the aim is to explore breast cancer dataset. The features of the dataset are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. This data analysis is useful to predict the breast cancer cells in human body.

let see what we have in our data set:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 569 entries, 0 to 568
Data columns (total 32 columns):

 #   Column                      Non-Null Count  Dtype  
---  ------                      --------------  -----  
 0   ID                          569 non-null    int64  
 1   diagnosis                   569 non-null    object 
 2   radius_mean                 569 non-null    float64
 3   texture_mean                569 non-null    float64
 4   perimeter_mean              569 non-null    float64
 5   area_mean                   569 non-null    float64
 6   smoothness_mean             569 non-null    float64
 7   compactness_mean            569 non-null    float64
 8   concavity_mean              569 non-null    float64
 9   concave_points_mean         569 non-null    float64
 10  symmetry_mean               569 non-null    float64
 11  fractal_dimension_mean      569 non-null    float64
 12  radius_sd_error             569 non-null    float64
 13  texture_sd_error            569 non-null    float64
 14  perimeter_sd_error          569 non-null    float64
 15  area_sd_error               569 non-null    float64
 16  smoothness_sd_error         569 non-null    float64
 17  compactness_sd_error        569 non-null    float64
 18  concavity_sd_error          569 non-null    float64
 19  concave_points_sd_error     569 non-null    float64
 20  symmetry_sd_error           569 non-null    float64
 21  fractal_dimension_sd_error  569 non-null    float64
 22  radius_worst                569 non-null    float64
 23  texture_worst               569 non-null    float64
 24  perimeter_worst             569 non-null    float64
 25  area_worst                  569 non-null    float64
 26  smoothness_worst            569 non-null    float64
 27  compactness_worst           569 non-null    float64
 28  concavity_worst             569 non-null    float64
 29  concave_points_worst        569 non-null    float64
 30  symmetry_worst              569 non-null    float64
 31  fractal_dimension_worst     569 non-null    float64
dtypes: float64(30), int64(1), object(1)
memory usage: 142.4+ KB

So we have 569 records against 32 columns and all of them have 569 non-null records and the data type is float64.



![alt text](https://github.com/ibra-him766/Advanced-Data-Science-Final-Project/Image/target_column.png)
