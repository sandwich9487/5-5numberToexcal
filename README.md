# 簡介
此程式碼作為一次python與excal互動練習，功能為在jupyter上渲染5*5的按鈕，並儲存該按鈕對應的值(紅色為0、綠色為1)，並填入excal做為一筆資料，可提供於網路模型訓練。
## 渲染展示
![選染展示](https://github.com/sandwich9487/5-5numberToexcal/blob/d9b6980f211d05a8e6e6bfd86f6a6762c38c4a8b/image/matrix.png)
# save_to_excel
點選保存後，會自動將矩陣以行為優先，逐行輸入excal，形成1*26的向量(含label)。
# 環境設置
建議在jupyter上執行
* pandas
* ipywidgets
* IPython
* openpyxl
* os
