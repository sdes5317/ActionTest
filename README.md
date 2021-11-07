# 練習Github Action常用的功能

### Zip And Release Sample.yml  
當push觸發時,自動使用Tag當作title,並zip指定檔案發佈到Release  
由於Tag完整的名稱為refs/tags/v*  
這裡使用的兩種取得tag version並設定成變數的方法
