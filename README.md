# Music Genre Recognition
Network tour of data sciences project

For this project we use the Free Music Archive (FMA) dataset. it is a free and open library.
The goal of this project is to recognize music genre from a track. We are
working with music from the genres "Rock","Hip-hop","Experimental" and "Electronic". Do we observe distinct features for every genre and can we identify them?
To answer those questions, we are building a similarity graph between music tracks and training Machine Learning model in order to be able to predict their genre and classify them.

## Report link
https://www.overleaf.com/read/hhmjtyryqgtn

## Structure

### ExtraTreesClassifier

Notebook containing the Extra Trees Classifier model, to run it you need to produce the "data.pkl" file from the "full_data_creation.ipynb" notebook and put it in the folder.

### Music Genre Recognition.ipynb

Notebook containig all the other models tested using the 4 genres: "Rock","Hip-hop","Experimental" and "Electronic". To run it you need to produce the "data_4.pkl" file from the "Data-Creation.ipynb" notebook and put it in the same folder as the notebook.

### Graph_project.ipynb

Notebook containig the visualization of the genres. To run it you need to produce the "data.pkl" file from the "full_data_creation.ipynb" notebook and put it in the same folder as the notebook.

### full_data_creation.ipynb

Notebook extracting the whole data from the dataset and creating the "data.pkl" file.

### Data-Creation.ipynb

Notebook extracting the data from the dataset only for the 4 genres: "Rock","Hip-hop","Experimental" and "Electronic" and creating the "data_4.pkl" file.
