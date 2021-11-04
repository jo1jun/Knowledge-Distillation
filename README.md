# Knowledge-Distillation

## Knowledge_Distillation_Classification.ipynb
task : image classification 

paper : Distilling the Knowledge in a Neural Network

pdf : https://arxiv.org/pdf/2102.00650
### dataset
CIFAR10
### result

#### [teacher] : CNN + cross-entropy-loss

Got 7398 / 10000 correct (73.98)

Average Inference Time :  0.0010553135234079543

#parameters : 435550

#### [student_solo] : small CNN + cross-entropy-loss

Got 6974 / 10000 correct (69.74)

Average Inference Time :  0.0008367368370104747

#parameters : 62430

#### [student_kd] : small CNN + knowledge-distillation-loss

Got 7216 / 10000 correct (72.16)

Average Inference Time :  0.0008491300473547286

#parameters : 62430

## Knowledge_Distillation_Regression.ipynb
task : object detection
