# Distracted Driver Detection

## 使用軟件
Python 3.6.3 :: Anaconda custom (64-bit)
## 使用庫與版本
#### 建構卷積神經網路：
tensorflow-gpu            1.6.0
keras                     	  2.1.4
#### 數據處理、讀寫文本：
numpy                        1.14.2
pandas                    	  0.20.3
#### 圖像處理：
opencv-python             3.4.1
ipython                   	  6.1.0
#### 繪製統計數據：
matplotlib                	  2.1.0
seaborn                   	  0.8.0
#### 提交項目：
kaggle                    	  1.3.3
#### 儲存參數：
h5py                      	  2.7.0
#### 繪製進度條：
tqdm                      	  4.11.2
## 數據來源
https://www.kaggle.com/c/state-farm-distracted-driver-detection/data

## 檔案說明
model select.ipynb：記錄從建構模型到產生預測結果使用的代碼，包含特徵的可視化與整合預測結果。
distracted_driver_detection.ipynb：包含調適部分模型並將特徵的可視化與繪製Heatmap的代碼。
