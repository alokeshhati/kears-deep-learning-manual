# kears-deep-learning-manual

for traing the dataset use the below link to download the dataset and unzip the dataset.
https://drive.google.com/file/d/1H8qOukJHxjPDC77QVs4xVU0bQ4Kfm0fq/view?usp=sharing

Run the below coommand for traing and testing the dataset

python train_simple_nn.py --dataset animals --model output/simple_nn.model --lable-bin output/simple_nn_lb.pickle --plot output/simple_nn_plot.png

python predict.py --image images/panda.jpg --model output/simple_nn.model --label-bin output/simple_nn_lb.pickle --width 32 --height 32 --flatten 1
