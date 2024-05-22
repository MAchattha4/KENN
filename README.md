# Knowledge Enchanced Neural Network (KENN)

KENN is hybrid forecasting model that fuses knowledge driven systems (KDS) with Deep Neural Networks (DNN). This repo shares the code of KENN in interactive python notebook (iPython).
## Get Started

1. All the dataset should be placed under 'data' folder. All the knowledge predictions should be placed under 'knowledge_preds' folder. Knowledge predictions for illness, M3 and energy datasets are included in the github. Other files were rather big to be uploaded. However, they can be requested.
2. Each iPython notebook has comments in cells that requires explanations to help in running the code 

# Files

## KDS

KDS.ipynb shares the code to get KDS predictions. Change the path in cell 3 to correspond to the path of data file. The output of the final cell is the prediction given by the KDS.

## KENN

File KENN_for SOTA comparison_1.ipynb contains the code for the KENN framework. Each cell contains comments to guide in training and reproducing the results of the Paper.
