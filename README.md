# TinyImagenet-EIP3

 Tried resnet50, heavily overfitted
 
 Tried resnet18, better than resnet50 but still overfitting
 
 Increased image size to 112x112 since receptive field of resnet18 is high, got max 56% validation accuracy
 
 Scrapped resnet and created custom densenet architecure and reached max of 60.51 accuracy after training on 32x32 20x20 and 64x64
 
 To-do :- Class-based training based on which classes are underperforming
 
 Key Helper in accuracy jump :- Lr tuning
