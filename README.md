# Comparative Analysis of Optimization Algorithms for Tomato Leaf Disease Detection
This repository contains the implementation and experimental comparison of multiple optimization algorithms 
used with the Multi-Axis Vision Transformer (MaxViT) deep learning model for tomato leaf disease detection 
in the context of precision agriculture.

## Model
- Multi-Axis Vision Transformer (MaxViT)

## Optimizers Compared
- SophiaG
- AdamW
- Adam
- Adagrad
- RMSprop
- SGD
## Dataset
Tomato Leaf subset of the PlantVillage dataset.

**Table:** Comparison of different optimization algorithms applied during training of the Multi-Axis Vision Transformer (MaxViT) model for tomato leaf disease classification. SophiaG achieved the highest convergence and best overall performance compared to other optimizers.
| Optimizer| F1 Score | Recall | Precision | Overall Accuracy |
|----------|---------:|-------:|----------:|-----------------:|
| SophiaG  | 0.9982   | 0.9982 | 0.9982    | 1.00             |
| AdamW    | 0.9980   | 0.9980 | 0.9980    | 1.00             |
| Adam     | 0.9970   | 0.9970 | 0.9970    | 1.00             |
| RMSprop  | 0.9961   | 0.9961 | 0.9961    | 1.00             |
| SGD      | 0.9943   | 0.9943 | 0.9943    | 0.99             |
| Adagrad  | 0.9832   | 0.9832 | 0.9832    | 0.98             |


## Key Findings
The SophiaG optimizer demonstrated:
- Faster convergence
- More stable training curves
- Higher validation accuracy

## Citation
If you use this repository, please cite our paper:
"Comparative Analysis of Optimization Algorithms for Tomato Leaf Disease Detection Using Multi-Axis Vision Transformer in Precision Agriculture"

## Author
Rafiullah Rafi  
Deportment of Agricultural Engineering, Afghanisatan National Agricultural Sciences and Technology University(ANASTU), Kandahar, Afghanistan  
Email: r.rafi@anastu.edu.af
