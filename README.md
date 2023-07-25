# ERA_7
# Target:15 epochs, test accuracy 99.4 %, and number of parameters 8K
model.py file contains Model_1, Model_2 and Model_3 classes
# model 1 Architecture 
<img width="626" alt="model 1 " src="https://github.com/katipallyvig8899/ERA_7/assets/45558037/11777771-0780-46e9-9dca-d012e1fdac38">
# performance of the model1
EPOCH: 0
Loss=0.1457282155752182 Batch_id=937 Accuracy=92.46: 100%|██████████| 938/938 [00:24<00:00, 38.79it/s]

Test set: Average loss: 0.0678, Accuracy: 9816/10000 (98.16%)

EPOCH: 1
Loss=0.023362061008810997 Batch_id=937 Accuracy=98.12: 100%|██████████| 938/938 [00:26<00:00, 35.59it/s]

Test set: Average loss: 0.0570, Accuracy: 9823/10000 (98.23%)

EPOCH: 2
Loss=0.037081148475408554 Batch_id=937 Accuracy=98.51: 100%|██████████| 938/938 [00:24<00:00, 38.73it/s]

Test set: Average loss: 0.0427, Accuracy: 9853/10000 (98.53%)

EPOCH: 3
Loss=0.01783006638288498 Batch_id=937 Accuracy=98.79: 100%|██████████| 938/938 [00:24<00:00, 38.89it/s]

Test set: Average loss: 0.0379, Accuracy: 9874/10000 (98.74%)

EPOCH: 4
Loss=0.04358142241835594 Batch_id=937 Accuracy=98.98: 100%|██████████| 938/938 [00:22<00:00, 42.36it/s]

Test set: Average loss: 0.0335, Accuracy: 9891/10000 (98.91%)

EPOCH: 5
Loss=0.016738703474402428 Batch_id=937 Accuracy=99.02: 100%|██████████| 938/938 [00:23<00:00, 40.76it/s]

Test set: Average loss: 0.0356, Accuracy: 9884/10000 (98.84%)

EPOCH: 6
Loss=0.003819554578512907 Batch_id=937 Accuracy=99.08: 100%|██████████| 938/938 [00:20<00:00, 45.69it/s]

Test set: Average loss: 0.0290, Accuracy: 9910/10000 (99.10%)

EPOCH: 7
Loss=0.00796925462782383 Batch_id=937 Accuracy=99.16: 100%|██████████| 938/938 [00:20<00:00, 44.77it/s]

Test set: Average loss: 0.0230, Accuracy: 9924/10000 (99.24%)

EPOCH: 8
Loss=0.04366568848490715 Batch_id=937 Accuracy=99.31: 100%|██████████| 938/938 [00:23<00:00, 40.48it/s]

Test set: Average loss: 0.0229, Accuracy: 9927/10000 (99.27%)

EPOCH: 9
Loss=0.0019994014874100685 Batch_id=937 Accuracy=99.27: 100%|██████████| 938/938 [00:22<00:00, 42.07it/s]

Test set: Average loss: 0.0249, Accuracy: 9917/10000 (99.17%)

EPOCH: 10
Loss=0.004118768498301506 Batch_id=937 Accuracy=99.31: 100%|██████████| 938/938 [00:22<00:00, 41.65it/s]

Test set: Average loss: 0.0227, Accuracy: 9929/10000 (99.29%)

EPOCH: 11
Loss=0.003974624909460545 Batch_id=937 Accuracy=99.39: 100%|██████████| 938/938 [00:22<00:00, 41.65it/s]

Test set: Average loss: 0.0208, Accuracy: 9932/10000 (99.32%)

EPOCH: 12
Loss=0.011034891940653324 Batch_id=937 Accuracy=99.43: 100%|██████████| 938/938 [00:22<00:00, 41.57it/s]

Test set: Average loss: 0.0252, Accuracy: 9925/10000 (99.25%)

EPOCH: 13
Loss=0.0058160703629255295 Batch_id=937 Accuracy=99.41: 100%|██████████| 938/938 [00:21<00:00, 43.13it/s]

Test set: Average loss: 0.0240, Accuracy: 9927/10000 (99.27%)

EPOCH: 14
Loss=0.012910689227283001 Batch_id=937 Accuracy=99.42: 100%|██████████| 938/938 [00:21<00:00, 42.99it/s]

Test set: Average loss: 0.0218, Accuracy: 9934/10000 (99.34%)


# Output plots of model 1
<img width="1244" alt="Screenshot 2023-07-24 at 3 04 42 AM" src="https://github.com/katipallyvig8899/ERA_7/assets/45558037/d8a5e045-9a6f-4529-8fba-80ebd1fd61d6">

# Results 
-> Parameters: 7.7k
-> Best Train Accuracy: 99.43
-> Best Test Accuracy: 99.34 (14th Epoch)
# Method and Analysis
Created the model skeleton and also applied batch normalization. model is underfitting at starting but after few epochs model is overfitting. We are getting best test accuracy around 99.34 % but still we are not getting our target accuracy 99.4 % within 15 epochs.

# MOdel 2 
# performance of the Model 2
EPOCH: 0
Loss=0.12242922931909561 Batch_id=937 Accuracy=89.67: 100%|██████████| 938/938 [00:53<00:00, 17.56it/s]

Test set: Average loss: 0.0684, Accuracy: 9799/10000 (97.99%)

EPOCH: 1
Loss=0.06301453709602356 Batch_id=937 Accuracy=97.40: 100%|██████████| 938/938 [00:49<00:00, 18.90it/s]

Test set: Average loss: 0.0421, Accuracy: 9858/10000 (98.58%)

EPOCH: 2
Loss=0.022558171302080154 Batch_id=937 Accuracy=97.73: 100%|██████████| 938/938 [00:49<00:00, 19.10it/s]

Test set: Average loss: 0.0437, Accuracy: 9850/10000 (98.50%)

EPOCH: 3
Loss=0.007890741340816021 Batch_id=937 Accuracy=98.09: 100%|██████████| 938/938 [00:47<00:00, 19.73it/s]

Test set: Average loss: 0.0329, Accuracy: 9890/10000 (98.90%)

EPOCH: 4
Loss=0.010708306916058064 Batch_id=937 Accuracy=98.19: 100%|██████████| 938/938 [00:48<00:00, 19.28it/s]

Test set: Average loss: 0.0350, Accuracy: 9890/10000 (98.90%)

EPOCH: 5
Loss=0.05916133150458336 Batch_id=937 Accuracy=98.42: 100%|██████████| 938/938 [00:47<00:00, 19.73it/s]

Test set: Average loss: 0.0316, Accuracy: 9908/10000 (99.08%)

EPOCH: 6
Loss=0.012666337192058563 Batch_id=937 Accuracy=98.35: 100%|██████████| 938/938 [00:48<00:00, 19.23it/s]

Test set: Average loss: 0.0312, Accuracy: 9908/10000 (99.08%)

EPOCH: 7
Loss=0.03272470086812973 Batch_id=937 Accuracy=98.56: 100%|██████████| 938/938 [00:50<00:00, 18.62it/s]

Test set: Average loss: 0.0235, Accuracy: 9931/10000 (99.31%)

EPOCH: 8
Loss=0.1013830378651619 Batch_id=937 Accuracy=98.51: 100%|██████████| 938/938 [00:47<00:00, 19.54it/s]

Test set: Average loss: 0.0228, Accuracy: 9933/10000 (99.33%)

EPOCH: 9
Loss=0.00794896949082613 Batch_id=937 Accuracy=98.48: 100%|██████████| 938/938 [00:47<00:00, 19.79it/s]

Test set: Average loss: 0.0265, Accuracy: 9917/10000 (99.17%)

EPOCH: 10
Loss=0.004201823379844427 Batch_id=937 Accuracy=98.54: 100%|██████████| 938/938 [00:48<00:00, 19.24it/s]

Test set: Average loss: 0.0214, Accuracy: 9942/10000 (99.42%)

EPOCH: 11
Loss=0.03102811798453331 Batch_id=937 Accuracy=98.67: 100%|██████████| 938/938 [00:48<00:00, 19.43it/s]

Test set: Average loss: 0.0225, Accuracy: 9935/10000 (99.35%)

EPOCH: 12
Loss=0.023701343685388565 Batch_id=937 Accuracy=98.75: 100%|██████████| 938/938 [00:48<00:00, 19.35it/s]

Test set: Average loss: 0.0205, Accuracy: 9946/10000 (99.46%)

EPOCH: 13
Loss=0.0055982805788517 Batch_id=937 Accuracy=98.72: 100%|██████████| 938/938 [00:49<00:00, 18.80it/s]

Test set: Average loss: 0.0228, Accuracy: 9934/10000 (99.34%)

EPOCH: 14
Loss=0.01382297370582819 Batch_id=937 Accuracy=98.76: 100%|██████████| 938/938 [00:48<00:00, 19.29it/s]

Test set: Average loss: 0.0194, Accuracy: 9948/10000 (99.48%)
# Output plots of model 2

<img width="1246" alt="Screenshot 2023-07-24 at 3 18 32 AM" src="https://github.com/katipallyvig8899/ERA_7/assets/45558037/d1422863-c5e3-4667-b799-5537841e1c9e">

# Result 
-> Parameters: 7.7k
-> Best Train Accuracy: 98.76
-> Best Test Accuracy: 99.48
# Method
 model_2 is same as model 1 we used same architecture but we added dropout to each layer to improve performance (avoid overfitting).


 # Model 3 
 # performance of the Model 3
 EPOCH: 0
Loss=0.10955826938152313 Batch_id=937 Accuracy=89.72: 100%|██████████| 938/938 [00:50<00:00, 18.70it/s]

Test set: Average loss: 0.0689, Accuracy: 9792/10000 (97.92%)

EPOCH: 1
Loss=0.04325434938073158 Batch_id=937 Accuracy=97.42: 100%|██████████| 938/938 [00:45<00:00, 20.72it/s]

Test set: Average loss: 0.0444, Accuracy: 9852/10000 (98.52%)

EPOCH: 2
Loss=0.016473351046442986 Batch_id=937 Accuracy=97.74: 100%|██████████| 938/938 [00:44<00:00, 21.14it/s]

Test set: Average loss: 0.0490, Accuracy: 9838/10000 (98.38%)

EPOCH: 3
Loss=0.014336732216179371 Batch_id=937 Accuracy=98.11: 100%|██████████| 938/938 [00:44<00:00, 21.23it/s]

Test set: Average loss: 0.0347, Accuracy: 9885/10000 (98.85%)

EPOCH: 4
Loss=0.019359659403562546 Batch_id=937 Accuracy=98.24: 100%|██████████| 938/938 [00:45<00:00, 20.66it/s]

Test set: Average loss: 0.0332, Accuracy: 9890/10000 (98.90%)

EPOCH: 5
Loss=0.056771453469991684 Batch_id=937 Accuracy=98.42: 100%|██████████| 938/938 [00:45<00:00, 20.75it/s]

Test set: Average loss: 0.0352, Accuracy: 9888/10000 (98.88%)

EPOCH: 6
Loss=0.005922118667513132 Batch_id=937 Accuracy=98.62: 100%|██████████| 938/938 [00:44<00:00, 21.18it/s]

Test set: Average loss: 0.0224, Accuracy: 9930/10000 (99.30%)

EPOCH: 7
Loss=0.020830675959587097 Batch_id=937 Accuracy=98.73: 100%|██████████| 938/938 [00:46<00:00, 20.14it/s]

Test set: Average loss: 0.0219, Accuracy: 9937/10000 (99.37%)

EPOCH: 8
Loss=0.13904517889022827 Batch_id=937 Accuracy=98.77: 100%|██████████| 938/938 [00:44<00:00, 21.07it/s]

Test set: Average loss: 0.0218, Accuracy: 9934/10000 (99.34%)

EPOCH: 9
Loss=0.010139815509319305 Batch_id=937 Accuracy=98.71: 100%|██████████| 938/938 [00:45<00:00, 20.79it/s]

Test set: Average loss: 0.0229, Accuracy: 9932/10000 (99.32%)

EPOCH: 10
Loss=0.006060339976102114 Batch_id=937 Accuracy=98.73: 100%|██████████| 938/938 [00:45<00:00, 20.63it/s]

Test set: Average loss: 0.0238, Accuracy: 9933/10000 (99.33%)

EPOCH: 11
Loss=0.019898783415555954 Batch_id=937 Accuracy=98.77: 100%|██████████| 938/938 [00:45<00:00, 20.74it/s]

Test set: Average loss: 0.0203, Accuracy: 9936/10000 (99.36%)

EPOCH: 12
Loss=0.02482300065457821 Batch_id=937 Accuracy=98.83: 100%|██████████| 938/938 [00:44<00:00, 21.32it/s]

Test set: Average loss: 0.0204, Accuracy: 9936/10000 (99.36%)

EPOCH: 13
Loss=0.005672494415193796 Batch_id=937 Accuracy=98.82: 100%|██████████| 938/938 [00:45<00:00, 20.70it/s]

Test set: Average loss: 0.0208, Accuracy: 9939/10000 (99.39%)

EPOCH: 14
Loss=0.013979372568428516 Batch_id=937 Accuracy=98.82: 100%|██████████| 938/938 [00:44<00:00, 20.95it/s]

Test set: Average loss: 0.0215, Accuracy: 9933/10000 (99.33%)
# Output plots of model 3

<img width="1246" alt="Screenshot 2023-07-24 at 3 33 07 AM" src="https://github.com/katipallyvig8899/ERA_7/assets/45558037/2b211557-0258-4a27-beef-4f113467b670">

# results 
-> Parameters: 7.7k
-> Best Train Accuracy: 98.83
-> Best Test Accuracy: 99.39(13th epoch)

# Method
 same as model 2. We added step lr to get consistent accuracy. We are getting best test accuracy around 99.39 % but still we are not getting our target accuracy 99.4 % within 15 epochs.

 









