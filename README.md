# Optimizing Wind Farm Economics through Python Modelling and Simulation

Wind farm economics were improved through the development of a Python-based cabling optimization model and integration of that into the LandBOSSE model. The LandBOSSE model was further modified to enhance its ability to accommodate irregular wind farm layouts. The project's success was demonstrated through simulations and case studies.

The project significantly enhances wind farm economics and helps in accurate calculations of the Balance of Plant costs for wind farms,   generating more accurate economic results that mirror real-world scenarios more closely.

## Cable Optimization model

Input -  Turbine coordinates, Substation Coordinates and Turbine Rated Power

Output - Total Cabling Costs, Total Connection Costs, Total Cabling length

*Created a comprehensive database that includes cabling specifications.
*Developed a specialized class to optimize cable length between turbines by employing a minimum spanning tree.
*Designed a class to determine the specific cable type needed for each connection.
*The main class seamlessly integrates all these components to deliver the final output and visualize the results.


Flow Chart for the Cable Optimization model - https://drive.google.com/file/d/1UJrp9X4oTxdnvE9nN2RzYFZoJZObinD1/view?usp=sharing

Result Visualization - https://drive.google.com/file/d/1yEDIGIHYGysfJYDdjWPyLpMrD1aQBkNu/view?usp=sharing

This model is integrated into the updated LandBOSSE model

## Original LandBOSSE model 

The Github repository for the original LandBOSSE model can be found here - https://github.com/WISDEM/LandBOSSE.git

Read this for diving deeper into the model - https://www.nrel.gov/docs/fy19osti/72201.pdf

This is the original LandBOSSE model to which further modifications are made.


## Updated LandBOSSE model 

The google drive link for LandBOSSE model can be found here - [[https://drive.google.com/drive/folders/1gJj-m61e4zeGtEx3Jzqwq_22JqeaxbT6](https://drive.google.com/drive/folders/1gJj-m61e4zeGtEx3Jzqwq_22JqeaxbT6?usp=sharing)]


Input - Turbine and Substation Coordinates
(Additional inputs are retrieved from an Excel-based database located in the "input" folder, it is similar to original LandBOSSE model)

Output - The generated output is an Excel spreadsheet within the database, stored in the "output" folder. The result structure is similar to that of original LandBOSSE model


FLow char for the LandBOSSE model


