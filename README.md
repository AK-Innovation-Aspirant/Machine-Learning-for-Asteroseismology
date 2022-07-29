 My job throughout the internship was to determine the parameters of a star subclass called Gamma Doradus stars where I was given simulated frequency data for the corresponding stars and the corresponding parameters. In this repository, you will find attached the raw data as well as several different approaches on the raw data. These were coded on the Tensorflow library.
 
Important Notes: 

1. For all the models, the files have been loaded based on the Google Drive file path. Please change the command to reflect your files according to where you run the repository.
2. There are processed frequency data files which are too large to be uploaded here. Therefore, they are attached in the Google Drive link here:
https://drive.google.com/drive/folders/190Mvrx6QPo7SA_TWf2QRpfEuqm_16sRM?usp=sharing. Please download any one of the two files. One is in float format and the other in integer format depending on your system's storage.

3. For few files, I have taken the first 20000 points for training the model. Please feel free to change this before running the file. In the processed data, you will only find the first 2 parameters in separate dataframes as those 2 are the most crucial parameters and the rest of the parameters can be calculated with them. Therefore, it is crucial to get a good result on the first two!
4. Here is the internship journal I maintained - https://docs.google.com/document/d/1w4rzYoEQIInOOh4ttYrjsNuCLTZT_ACjBCg7f_3zxAY/edit?usp=sharing containing personal notes, past approaches ,experiments carried out and potential new avenues of research. This will aid in trying out new experiments or refactoring the code for older experiments to improve the results
