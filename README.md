# Auto-Rickshaw-Number-Plate-Dataset
This repository contains the annotated data set for 25 auto rickshaw images with corresponding number plate details.

**Steps to use: (User Interface)**

Open the via.html file and load the Pradeep_Elavarasan_EIP3-1B.json. Now you can view all the images with their corresponding number plate details. You can also create new annotation using the via.html file. 

Example:
![my_image](/Object%20Recognition%20Example%20-%20Autorickshaw.JPG)

**Steps to use: (Json)**

If you want to consume the data annotation, you can directly use the images files along with the Pradeep_Elavarasan_EIP3-1B.json file. 

Example:

"IMG_20190226_105153.jpg329468":{"filename":"IMG_20190226_105153.jpg","size":329468,"regions":[{"shape_attributes":{"name":"rect","x":647,"y":321,"width":549,"height":636},"region_attributes":{"Class":"AUTO"}},{"shape_attributes":{"name":"rect","x":1010,"y":741,"width":89,"height":53},"region_attributes":{"Class":"KA04AA2801"}}],"file_attributes":{}}
