# AI-Based Multi-Axis Vision Transformer model with Optimizer Analysis for Tomato Leaf Disease Detection in Precision Agriculture
This repository contains the implementation and experimental comparison of multiple optimization algorithms 
used with the Multi-Axis Vision Transformer (MaxViT) deep learning model for tomato leaf disease detection 
in the context of precision agriculture.

## Model
- Multi-Axis Vision Transformer (MaxViT)

## Optimizers Compared
- AdamW
- SophiaG
- Adam
- Adagrad
- RMSprop
- SGD
## Dataset
Tomato Leaf subset of the PlantVillage dataset.

## Results and analysis 
**Table:** Comparison of different optimization algorithms applied during training of the Multi-Axis Vision Transformer (MaxViT) model for tomato leaf disease classification. SophiaG achieved the highest convergence and best overall performance compared to other optimizers.
| Optimizer| F1 Score | Recall | Precision | Overall Accuracy |
|----------|---------:|-------:|----------:|-----------------:|
| AdamW    | 0.9989   | 0.9989 | 0.9989    | 1.00             |
| SophiaG  | 0.9982   | 0.9982 | 0.9982    | 1.00             |
| Adam     | 0.9970   | 0.9970 | 0.9970    | 1.00             |
| RMSprop  | 0.9961   | 0.9961 | 0.9961    | 1.00             |
| SGD      | 0.9943   | 0.9943 | 0.9943    | 0.99             |
| Adagrad  | 0.9832   | 0.9832 | 0.9832    | 0.98             |


## Key Findings
The AdamW and  SophiaG optimizers demonstrated:
- Faster convergence
- More stable training curves
- Higher validation accuracy

## 🚀 Try Online (Google Colab)
You can directly test the pretrained MaxViT tomato leaf disease model online:

👉 Open Colab Notebook:
[https://colab.research.google.com/your-link-here](https://colab.research.google.com/drive/1uvE08WbHIDigVDjdWUpL4fIYP2j4DIuu?usp=sharing)

Steps:
1. Open the notebook
2. Run all cells
3. Upload a tomato leaf image
4. Get disease prediction with confidence

## Author
Rafiullah Rafi  
Department of Agricultural Engineering, Afghanisatan National Agricultural Sciences and Technology University(ANASTU), Kandahar, Afghanistan  
Email: r.rafi@anastu.edu.af
