深度學習專案設計的期末專題，主題是辦公文具用品分類。探討了利用機械手臂將凌亂的文具用品分類至指定位置，打造良好辦公環境的可能性。
報告重點如下：

●  資料集建立：
  ○  拍攝了五種文具用品（筆、膠水、釘書機、橡皮擦、長尾夾）和三種辦公桌面（電腦桌、工作桌、白桌）的圖像。
  ○  他們採用了拍攝真實圖像和合成圖像的方式收集資料，並透過資料擴增技術，最終每個文具用品的樣本數達到 500 張。
  
●  模型選擇與實作：
  ○  比較了 CNN、ResNet101 和 YOLOv11 三種模型的優缺點，並分別進行了模型訓練。
  ○  詳細介紹每個模型的架構和訓練過程。
  
●  成果分析：
  ○  CNN 模型的準確率為 60.80%，但存在過擬合問題。
  ○  ResNet101 模型的準確率較高，泛化能力良好。
  ○  YOLOv11 模型表現最佳，準確率約為 90%，能夠準確識別和定位文具用品。
  
●  實際成果與未來展望：
  ○  YOLOv11 模型被認為是最符合預期成果的方案。
  ○  希望未來能結合機器人、大型語言模型和電腦視覺等技術，讓使用者透過指令或語音控制機械手臂，將文具用品歸位。
  ○  本報告的關鍵發現是，即使在資料集有限的情況下，透過選擇合適的模型和資料擴增技術，也能夠訓練出高準確率的物件偵測模型。

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Final Project for Design of Deep Learning Course: Stationery Classification. This project explored the possibility of using robotic arms to classify scattered stationery items to designated locations, creating a better office environment.
Key points of the report:

●  Dataset Development:
  ○  Captured images of five types of stationery (pens, glue sticks, staplers, erasers, binder clips) and three types of office desks (computer desk, work desk, white desk).
  ○  They collected data through both real photography and synthetic images, and through data augmentation techniques, achieved 500 samples for each stationery item.

●  Model Selection and Implementation:
  ○  Compared the advantages and disadvantages of three models: CNN, ResNet101, and YOLOv11, and conducted training for each model.
  ○  Detailed introduction of each model's architecture and training process.

●  Results Analysis:
  ○  The CNN model achieved 60.80% accuracy but suffered from overfitting issues.
  ○  The ResNet101 model showed higher accuracy with good generalization capability.
  ○  The YOLOv11 model performed the best with approximately 90% accuracy, accurately identifying and localizing stationery items.

●  Practical Results and Future Prospects:
  ○  The YOLOv11 model was considered the most suitable solution meeting expected outcomes.
  ○  Future goals include integrating robotics, large language models, and computer vision technologies to enable users to control robotic arms through commands or voice input for stationery organization.
  ○  The key finding of this report is that even with limited datasets, high-accuracy object detection models can be trained through appropriate model selection and data augmentation techniques.
