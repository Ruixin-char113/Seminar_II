# 20250401-Yolov4、Yolov7及Yolov9的發展過程

## 基本資訊
* 日期: 2025 / 04 / 01
* 講者: 中央研究院資訊科學研究所特聘研究員 廖弘源 博士
* 題目: Yolov4、Yolov7及Yolov9的發展過程
* 關鍵字: **YOLO**、**物件偵測**

## 筆記
* 紀錄: 11363111 陳瑞鑫

### 科學家 vs 工程師
* 科學家用 系統性方法 解決 長期問題。
* 工程師用 已存在方法 解決 現有問題。

### Edge Detection
* 形成封閉曲線，方便segmentation。

### Visual Dictionary
* 2007 - 2010
* Classes: 21k, Images: 14M
* End to End 視覺字典
* ImageNet
    * Visual based dictionary
    * Feature extractor and classifier
    * 輸出辨識結果

### 發展時間
* 2013 R-CNN
* 2015 Fast R-CNN, Faster R-CNN, YOLOv1
* 2018 YOLOv3
* 2020 YOLOv4
* 2022 YOLOv7

### YOLOv4 發展
* 業界出題、學界解題
* Nvidia Jetson TX2: 運算力 5% - 7% GTX 1080 Ti
* 只能邊緣計算、不得傳回雲端。
* 智慧城市、交通

### 設計物件偵測系統須考量的基本議題
* network architecture
* feature integration method
* detection method
* loss function
* label assignment method
* training method

### 設計物件偵測系統考量及策略
* lightweight: 快、準
* 適用: cloud, local, and edge
* 參考現有方法

### Layer-level and Stage-level
* 只改 layer 不會形成語意。
* 不同的 stage 負責不同大小的物件。

### YOLOv9
* GELAN 保持前傳的資料、解決多層時影像模糊。
* Explicit: 明確定義, Implicit: 隱含。增加效果。

### 後續研究方向
* Image Captioning。
* 交通、生醫、追蹤生物活動。

### 提問: 如何看待研究
* 了解科學的核心、理論、過往。
* 簡單的生活。

> 本筆記僅作為 *書報討論(二) Seminar II* 課程筆記作業使用。