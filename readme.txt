README
Libraries required:-
1) Numpy
2) Pandas
3) Matplotlib.pyplot
4) Seaborn
5) SuSi
All the above libraries can be installed using pip
eg) pip install susi

The folder contains 2 .py files:- 
1) preprocessing.py  
2) main.py

In order to generate the results it is sufficient to run the main.py file directly.
The code will take quite some time as it trains a large model before printing the results and graphs.
The file preprocessing.py generates all the extracted features as .npy files that are used by the model. 
However a lot of mouse data has been removed from the folder mouse_data due to the file size restrictions.
As a result the generated pre-processed data will not be identical to the one already present and used by our model.
Because it takes a lot of time for the full dataset, the resultant 'data.npy' file has already been stored along with the codes. 

