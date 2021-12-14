# Color-Clustering-and-Detection-from-Image
The ML algorithm clusters different shades of colors given in the dataset. In addition it also detects the colors from images and states the name of the color as stated in the dataset

## Contributers
1. Johann Kyle Pinto 20BKT0009
2. Riya Mathew 20BKT0016

## Files
Main Code : [Color_Clustering_and_Detection.ipynb](Color_Clustering_and_Detection.ipynb)
<br>Dataset : [colors.csv](colors.csv)
<br>Test Image : [detect_color.jpg](detect_color.jpg)

## Libraries Used
1. [OpenCV](https://pypi.org/project/opencv-python/)
2. [numpy](https://numpy.org/install/)
3. [pandas](https://pandas.pydata.org/getting_started.html)
4. [matplotlib](https://matplotlib.org/stable/users/getting_started/index.html#installation-quick-start)
5. [textwrap](https://docs.python.org/3/library/textwrap.html)

## Steps to run the Program
1. Install the libraries required to run the program.
2. Execute all the cells of the Jupyter notebook.
3. You can view the clusters formed. To check for a random cluster execute 'getCluster(num)' in a new cell, where num is the cluster number.(<i>Note that the value of num should be between 1 to 130 since 130 clusters were formed using K-Means Algorithm</i>)
4. After execution of last cell, a new window will pop-up with the test image.
5. Double-Click on the location of the image on the new window, where you want to the name of the color used in that location of the image.
6. The name of the color will be displayed at the top of the screen in a rectangle.
7. Double-Click on another location of the image to detect a new color. 
8. To exit the window, press the ESC key.
