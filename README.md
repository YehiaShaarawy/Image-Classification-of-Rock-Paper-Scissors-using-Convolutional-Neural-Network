# Image Classification of Rock-Paper-Scissors using Convolutional Neural Network

## Dataset
Dataset used : https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors?select=README_rpc-cv-images.txt

The dataset contains a total of 2188 images with 300 x 200 pixels, that
correspond to the hand gestures of the Rock-Paper-Scissors game: ‘Rock’ (726
images), ‘Paper’ (710 images), and ‘Scissors’ (752 images). Here are few images
taken from the dataset:


<img width="151" alt="Picture3" src="https://github.com/YehiaSharawy/Image-Classification-of-Rock-Paper-Scissors-using-Convolutional-Neural-Network/assets/65984199/742323c4-c8d0-42ec-8622-e0c7c8019491">
<img width="151" alt="Picture2" src="https://github.com/YehiaSharawy/Image-Classification-of-Rock-Paper-Scissors-using-Convolutional-Neural-Network/assets/65984199/202351a9-7b46-4db2-835f-acc24260b4e2">
<img width="150" alt="Picture1" src="https://github.com/YehiaSharawy/Image-Classification-of-Rock-Paper-Scissors-using-Convolutional-Neural-Network/assets/65984199/c889dfbb-0233-4120-9cd2-24bee767eadc">

## Evaluation Metrics
<img width="255" alt="Picture4" src="https://github.com/YehiaSharawy/Image-Classification-of-Rock-Paper-Scissors-using-Convolutional-Neural-Network/assets/65984199/de5d682d-5faf-41e9-951a-89ec9d8700e2">
<img width="255" alt="Picture5" src="https://github.com/YehiaSharawy/Image-Classification-of-Rock-Paper-Scissors-using-Convolutional-Neural-Network/assets/65984199/2fff4757-3c49-431a-bacc-b488ddb59207">

The result above shows that the accuracy is increasing steadily while the loss is also reducing, for both train and validation dataset.

<img width="315" alt="Picture6" src="https://github.com/YehiaSharawy/Image-Classification-of-Rock-Paper-Scissors-using-Convolutional-Neural-Network/assets/65984199/587e6b11-1d44-4636-b555-335e9ac4b725">

Next we evaluate the validation data and we got <b>96%</b> accuracy, which is pretty high. We can test it by uploading new images and let the model predicts whether it is a paper, rock, or scissors gesture.
