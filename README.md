# Fine-tuned model for named entity recognition

This project present a notebook to create a fined-tuned Camembert model for named entity recognition.
It applys also the Distillation method to keep a maximum of performance, while reducing it's size by 50%.

this notebook use the labeled dataset of wikineural.

## Setup of the project

To run this project it is needed to run on GPU's supporting Cuda, this is why it was decided to use Kaggle giving a free access to the environnement and hardware needed.

First import this notebook to Kaggle, then choose for the Accelrator 'GPU' and turn on the internet.

Now you only have to run the notebook for the fine tuning to process.
Each fine tuning take around 15 minutes.
Only one epoch is used because we dont get an significant improvement by running more of them.

You can download the NER models produced by downloading the zip files produced in the kaggle sidebar.
