# make_ImageData_for_Labelme


## 用Labelme標記完後的json檔生成訓練資料


## 兩部分

### makeFromJson.py

- (Dataname).folder
  - (original_data).png
  - lable.png      
  - label_names.txt **(classes)**
  - label.viz.png **(原圖套上label作為mask)**


### makeTrainDataSet.py

- Data
  -  Train.folder
    -  image.folder
    -  label.folder

