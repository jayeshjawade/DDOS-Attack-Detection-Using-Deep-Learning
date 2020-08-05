# DDOS Attack Detection using Deep Learning
#Using Bidirectional LSTM based RNN to classify DDoS attack packets

The design of this classifier was inspired by [DeepDefense: Identifying DDoS Attack via Deep Learning](https://ieeexplore.ieee.org/document/7946998) paper. 

## Architecture of the model
![Model](model_brnn.png)


## Usage

Run the ```brnn_classifier.ipynb``` notebook.

## Results

### Plot of accuracy
![Plot of accuracy](BRNN_Model_Accuracy.png)

### Plot of loss
![Plot of loss](BRNN_Model_Loss.png)

The data set we used can be found here: https://www.unb.ca/cic/datasets/ids.html

Please refer to this paper for more information on the dataset: https://www.sciencedirect.com/science/article/pii/S0167404811001672

The exact data set we had used is https://gitlab.com/santhisenan/ids_iscx_2012_dataset.git


