# Audio processing using MLP and CNN artichectures
This project contains codes to process the raw audio data for dataset creation and build MLP and CCN models for real-time voice recognition with 4 classes. At last, we implemented this model on a simple game

## Dataset
we have not used any clean and pre-built dataset for this project instead of that  we used our self-made dataset. you can see the codes for preprocessing and also data augmentation in related notebooks\
this dataset contains 1628 audio folders(originally 814) that are separated into 4 groups: up, down, right, and left also it contains 6 .csv file 
(2 for each train, test, and validation) that are created using codes that are available for you to see\
it is worth mentioning that labels are encoded using ono-hot-encoding
## Models
in this project we used two different types of architecture for audio processing: MLP and CNN\
As a result of our noisy and small dataset, the MLP model works well in theoretical research but fails to classify in real-time experiments. So we used ensemble learning as a method to increase our model's real-time accuracy and it worked quite satisfiying\
CNN model just worked well and you can see the results in the codes mentioned the only drawback of it was that has a high computational cost and it will slow down our game

