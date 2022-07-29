 My job throughout the internship was to determine the parameters of a star subclass called Gamma Doradus stars where I was given simulated frequency data for the corresponding stars and the corresponding parameters. In this repository, you will find attached the raw data as well as several different approaches on the raw data. These were coded in Python on the Tensorflow library.
 
Important Notes: 

1. For all the models, the files have been loaded based on the Google Drive file path. Please change the command to reflect your files according to where you run the repository.
2. Few files of code may not be clearly visible since they are greater than 100KB or possess images of graphs.In this case, download the .ipynb files and run them using Jupyter Notebooks in Google Colab or Anaconda (these worked for me).
3. There are processed frequency data files which are too large to be uploaded here. Therefore, they are attached in the Google Drive link here:
https://drive.google.com/drive/folders/190Mvrx6QPo7SA_TWf2QRpfEuqm_16sRM?usp=sharing. Download any one of the two files. One is in float format and the other in integer format depending on your system's storage.

4. For few files, I have taken the first 20000 points for training the model. Please feel free to change this before running the file. In the processed data, you will only find the first 2 parameters in separate dataframes as those 2 are the most crucial parameters and the rest of the parameters can be calculated with them. Therefore, it is crucial to get a good result on the first two!
5. Here is the internship journal I maintained - https://docs.google.com/document/d/1w4rzYoEQIInOOh4ttYrjsNuCLTZT_ACjBCg7f_3zxAY/edit?usp=sharing containing personal notes, past approaches ,experiments carried out and potential new avenues of research. This will aid in trying out new experiments or refactoring the code for older experiments to improve the results

Future steps for the project:

1. There should ideally be atleast 40 classes in the experiments for it to be considered useful. The next update to the repo will be with using transformers as a part of the experiment. Either training a model from scratch or attempting to take a language model like BERT and fine-tuning it for this problem. 
2. The complex nature of the g_mode_spacing makes it difficult for the model to map. Fourier transforms did not smooth the signal as much as required so alternate methods. Alternate methods to decompose the data into an exponential or linear format need to be found.
3. Further experimentation with preprocessing of the inputs and the outputs to find a mapping which could model it the best.
4. Learning more about the underlying physics of these stars and the similarities with other stars. This helps in replicating the ML techniques they have utilised on the data.
