# Transformer from scratch
The goal of this repository is to implement the transformer model introduced in the paper "Attention is all you need" (chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) using PyTorch. On top of that, a couple of examples are included. The datasets used for the examples are IMDb (sentiment analysis dataset), and Spiking Heidelberg Digits, SHD (neuromorphic dataset consisting on audio recordings of ten different digits in English and German). 

The file transformer.py contains all the code needed to build the model. The file train.py includes the function used for training. The files SHD_model.py and imdb_model.py include the models used and the files imdbmain.py and SHDmain.py are the ones that must be executed for training. A folder with plots of the training results on each dataset is also available.  

