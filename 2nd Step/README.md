In this folder, two steps: TR3 and TR4 are performed

In TR3, dropout is added after each convolution layer. the value of dropout_value = 0.05

The parameters are still below 10k as shown in below:

![image](https://user-images.githubusercontent.com/79099957/213780278-a4f201ad-099c-4fc2-8754-9d3a2e22cdb7.png)

The results are shown as

EPOCH: 0
Loss=0.1580028086900711 Batch_id=468 Accuracy=94.22: 100%|██████████| 469/469 [00:13<00:00, 35.53it/s]

Test set: Average loss: 0.0532, Accuracy: 9833/10000 (98.33%)

EPOCH: 1
Loss=0.030721671879291534 Batch_id=468 Accuracy=98.04: 100%|██████████| 469/469 [00:12<00:00, 36.29it/s]

Test set: Average loss: 0.0407, Accuracy: 9869/10000 (98.69%)

EPOCH: 2
Loss=0.09047490358352661 Batch_id=468 Accuracy=98.39: 100%|██████████| 469/469 [00:12<00:00, 36.13it/s]

Test set: Average loss: 0.0337, Accuracy: 9885/10000 (98.85%)

EPOCH: 3
Loss=0.10459022969007492 Batch_id=468 Accuracy=98.62: 100%|██████████| 469/469 [00:12<00:00, 36.59it/s]

Test set: Average loss: 0.0326, Accuracy: 9888/10000 (98.88%)

EPOCH: 4
Loss=0.026270993053913116 Batch_id=468 Accuracy=98.77: 100%|██████████| 469/469 [00:12<00:00, 36.38it/s]

Test set: Average loss: 0.0324, Accuracy: 9896/10000 (98.96%)

EPOCH: 5
Loss=0.021535858511924744 Batch_id=468 Accuracy=98.84: 100%|██████████| 469/469 [00:12<00:00, 36.29it/s]

Test set: Average loss: 0.0359, Accuracy: 9896/10000 (98.96%)

EPOCH: 6
Loss=0.04381423071026802 Batch_id=468 Accuracy=98.86: 100%|██████████| 469/469 [00:12<00:00, 36.13it/s]

Test set: Average loss: 0.0321, Accuracy: 9893/10000 (98.93%)

EPOCH: 7
Loss=0.010768118314445019 Batch_id=468 Accuracy=98.99: 100%|██████████| 469/469 [00:13<00:00, 33.72it/s]

Test set: Average loss: 0.0278, Accuracy: 9908/10000 (99.08%)

EPOCH: 8
Loss=0.010660190135240555 Batch_id=468 Accuracy=98.98: 100%|██████████| 469/469 [00:13<00:00, 35.36it/s]

Test set: Average loss: 0.0279, Accuracy: 9916/10000 (99.16%)

EPOCH: 9
Loss=0.00953687448054552 Batch_id=468 Accuracy=99.09: 100%|██████████| 469/469 [00:13<00:00, 36.06it/s]

Test set: Average loss: 0.0268, Accuracy: 9909/10000 (99.09%)

EPOCH: 10
Loss=0.0174094345420599 Batch_id=468 Accuracy=99.13: 100%|██████████| 469/469 [00:13<00:00, 35.83it/s]

Test set: Average loss: 0.0280, Accuracy: 9912/10000 (99.12%)

EPOCH: 11
Loss=0.012952841818332672 Batch_id=468 Accuracy=99.17: 100%|██████████| 469/469 [00:13<00:00, 36.02it/s]

Test set: Average loss: 0.0250, Accuracy: 9914/10000 (99.14%)

EPOCH: 12
Loss=0.05176517739892006 Batch_id=468 Accuracy=99.14: 100%|██████████| 469/469 [00:13<00:00, 35.61it/s]

Test set: Average loss: 0.0259, Accuracy: 9918/10000 (99.18%)

EPOCH: 13
Loss=0.04374678060412407 Batch_id=468 Accuracy=99.21: 100%|██████████| 469/469 [00:13<00:00, 35.60it/s]

Test set: Average loss: 0.0271, Accuracy: 9911/10000 (99.11%)

EPOCH: 14
Loss=0.029208289459347725 Batch_id=468 Accuracy=99.15: 100%|██████████| 469/469 [00:13<00:00, 35.59it/s]
Test set: Average loss: 0.0259, Accuracy: 9912/10000 (99.12%)


In TR4, Global average pooling is added. The parameters are still below 10k

![image](https://user-images.githubusercontent.com/79099957/213780667-ded2ef93-5388-4ab0-a768-f9d4b8797808.png)

The results are shown as below

EPOCH: 0
Loss=0.09116557240486145 Batch_id=468 Accuracy=87.74: 100%|██████████| 469/469 [00:15<00:00, 31.01it/s]

Test set: Average loss: 0.0710, Accuracy: 9799/10000 (97.99%)

EPOCH: 1
Loss=0.02335911989212036 Batch_id=468 Accuracy=97.95: 100%|██████████| 469/469 [00:18<00:00, 25.40it/s]

Test set: Average loss: 0.0426, Accuracy: 9869/10000 (98.69%)

EPOCH: 2
Loss=0.04591448977589607 Batch_id=468 Accuracy=98.40: 100%|██████████| 469/469 [00:14<00:00, 31.44it/s]

Test set: Average loss: 0.0359, Accuracy: 9895/10000 (98.95%)

EPOCH: 3
Loss=0.050974126905202866 Batch_id=468 Accuracy=98.70: 100%|██████████| 469/469 [00:13<00:00, 34.11it/s]

Test set: Average loss: 0.0284, Accuracy: 9920/10000 (99.20%)

EPOCH: 4
Loss=0.0528484582901001 Batch_id=468 Accuracy=98.79: 100%|██████████| 469/469 [00:13<00:00, 34.24it/s]

Test set: Average loss: 0.0272, Accuracy: 9920/10000 (99.20%)

EPOCH: 5
Loss=0.09525609016418457 Batch_id=468 Accuracy=98.92: 100%|██████████| 469/469 [00:13<00:00, 34.38it/s]

Test set: Average loss: 0.0272, Accuracy: 9920/10000 (99.20%)

EPOCH: 6
Loss=0.013273607939481735 Batch_id=468 Accuracy=99.00: 100%|██████████| 469/469 [00:13<00:00, 33.75it/s]

Test set: Average loss: 0.0269, Accuracy: 9915/10000 (99.15%)

EPOCH: 7
Loss=0.009940025396645069 Batch_id=468 Accuracy=99.04: 100%|██████████| 469/469 [00:14<00:00, 32.59it/s]

Test set: Average loss: 0.0244, Accuracy: 9924/10000 (99.24%)

EPOCH: 8
Loss=0.037169698625802994 Batch_id=468 Accuracy=99.06: 100%|██████████| 469/469 [00:14<00:00, 33.48it/s]

Test set: Average loss: 0.0264, Accuracy: 9915/10000 (99.15%)

EPOCH: 9
Loss=0.005010946188122034 Batch_id=468 Accuracy=99.14: 100%|██████████| 469/469 [00:14<00:00, 33.43it/s]

Test set: Average loss: 0.0240, Accuracy: 9926/10000 (99.26%)

EPOCH: 10
Loss=0.015274940989911556 Batch_id=468 Accuracy=99.23: 100%|██████████| 469/469 [00:14<00:00, 33.35it/s]

Test set: Average loss: 0.0220, Accuracy: 9930/10000 (99.30%)

EPOCH: 11
Loss=0.031327854841947556 Batch_id=468 Accuracy=99.17: 100%|██████████| 469/469 [00:15<00:00, 30.78it/s]

Test set: Average loss: 0.0240, Accuracy: 9926/10000 (99.26%)

EPOCH: 12
Loss=0.010663620196282864 Batch_id=468 Accuracy=99.26: 100%|██████████| 469/469 [00:14<00:00, 33.49it/s]

Test set: Average loss: 0.0212, Accuracy: 9929/10000 (99.29%)

EPOCH: 13
Loss=0.02142675220966339 Batch_id=468 Accuracy=99.25: 100%|██████████| 469/469 [00:13<00:00, 34.04it/s]

Test set: Average loss: 0.0208, Accuracy: 9929/10000 (99.29%)

EPOCH: 14
Loss=0.004375254735350609 Batch_id=468 Accuracy=99.33: 100%|██████████| 469/469 [00:14<00:00, 32.91it/s]

Test set: Average loss: 0.0215, Accuracy: 9930/10000 (99.30%)




