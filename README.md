# Stacked-Denoising-Convolutional-Autoencoder (SDCAE-Pytorch)
The SDCAE model is implemented for PHM data. The scripst are public and based on Pytorch.

## Model and Environment:  
1. The SDCAE model and script are revised from the following previous wrok:  
https://github.com/ShayanPersonal/stacked-autoencoder-pytorch  

2. Please run "pip install -r requirements.txt" for Python=3.6  

## Run the model:  
1. Please run "python run_sdcae.py"   
2. Before training, prepare your dataset and both list_train.csv and list_test.csv  
3. The datasets can be refered in branch "main"-> folder "wav"  

## DataSet Description:   
1. There are three classes of data: Normal, NG1 and NG2.  
2. The data were measured from motor oscillation by a three-axis accelerator.  
3. The x, y and z data were divided and saved under different folders.  
4. Each data.csv contains about 60k ea points where measured time is 30 sec.  
  

![image](https://github.com/ChengWeiGu/stacked-denoising-autoencoder/blob/main/result.jpg)  
