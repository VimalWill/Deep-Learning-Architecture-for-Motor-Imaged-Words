# Deep Learning Approach for Motor Imaged Words

## Table of content 

1. General Note 
2. Review on Dataset 
3. Deep Learning Architecture 
4. Citation

## General Note

The aim to construct an interface between Human's brain and a computer pays a way to this research. The neural signals i.e., EEG Signals from the particular region in the human brain such as motor cortex or the regions related to motor activties to human muscles been collected and used as the data for the construction of neural network architecture. Signals were preprocessed with the various stages of signal processing methods and converted into both 1D spectrum and 2D matrices. The neural network architecture is constructed to interpert the actions realated to signals in both 1D and 2D.

## Review on Dataset 
The Dataset is used in the research is [Brain-Computer Interface III](https://www.bbci.de/competition/iii/). In the dataset, the basic human activities such as moving hands, legs etc been mapped with the respective neural signals from the motor cortex. Those signals are preprocessed to train the Artificial Intelligence model which can further predicts those activites with the generated signals from brain

## Deep Learning Architecture 
As the signals can be treatd as 1D as well as 2D, the construction of DL architectures are made up with Convolutional 1D and 2D as well. The convolutional layers are acting as feature selectors which picks up the best feature and push to LSTM layers which acts as the classifiers in the cases of both 1D and 2D signals. 

## Citation 
Please cite our article on utilizing our results or methods 
```
@article{vimal2023deep,
  title={Deep Learning Architecture for Motor Imaged Words},
  author={Vimal W and Gupta, Akshansh},
  journal={arXiv preprint arXiv:2308.10840},
  year={2023},
  eprint={2308.10840},
  archivePrefix={arXiv},
  primaryClass={q-bio.NC},
  doi={10.48550/arXiv.2308.10840}
}
```