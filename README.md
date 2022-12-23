# Multi-Tasks-NLP-Bert-Model

## Train multi-task of Name Entity recognition(NER), intent detection, fragment detection 3 tasks all together using Bert pretrained model and plugged in downstream tasks using a linear layer and drop-out layer.
## The multi-task is parameter sharing, while the downstream task's parameters are separate.
## The result of using multitask can increase the performance to 1 percent of 2 tasks out of 3 tasks compared with a baseline that is trained alone.

## See paper for more details

## Model Architecture


![Demo](doc/model_arc.jpg)

## Result

![Demo](doc/result.jpg)


