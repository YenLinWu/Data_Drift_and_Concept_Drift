# Kolmogorov-Smirnov Test  
> 吳彥霖 [![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yenlinwu/)   on March 3, 2023   

在監控模型飄移(Model Drift)的方法中， KS 檢定(Kolmogorov-Smirnov Test, KS Test)可用來偵測是否發生資料飄移(Data Drift)，係一種無母數統計檢定(Nonparametric Statistics)，主要係藉由比較兩樣本的累積分佈函數(Cumulative Distribution Function, CDF)，透過計算兩 CDF 彼此之間的最大差距，推論兩樣本是否源自於同一個母體分佈。

## Python 程式碼範例    

[![Colab](https://img.shields.io/badge/Python_Script-Google_Colab-yellow.svg)](https://colab.research.google.com/github/YenLinWu/Model_Drift/blob/dev/KS_Test/KS_Test.ipynb)  :point_left:

> Requirements : ![Python](https://img.shields.io/badge/Python-3.8.10-blue.svg) ![Numpy](https://img.shields.io/badge/NumPy-1.21.6-range.svg) ![Pandas](https://img.shields.io/badge/Pandas-1.3.5-range.svg) ![Matplotlib](https://img.shields.io/badge/Matplolib-3.2.2-range.svg) ![SciPy](https://img.shields.io/badge/SciPy-1.7.3-range.svg)    

> 範例說明:   
> 在 2022年 3月初鎳的交易市場中，發生了前所未見的暴漲，市場將此事件稱為「妖鎳事件」。本範例將應用 2021 年起每個交易日的鎳現金結算數據，且使用 KS 檢定來觀察鎳的交易市場，在事件發生前後的時間，資料是否產生明顯的偏移現象?
> <p align="left">
> <img width="550" src="./Imgs/Nickel_Price_Trend.png">
> </p>  
> 數據飄移的偵測結果:  
>  
> 偵測方法一 
> <p align="left">
> <img width="550" src="./Imgs/Data_Drift_Detection_in_KS_Test_with_fixed_1_sliding_window.gif">
> </p>
>
> 偵測方法二
> <p align="left">
> <img width="550" src="./Imgs/Data_Drift_Detection_in_KS_Test_with_unfixed_2_sliding_windows.gif">
> </p>

Back to [How to Detect Model Drift?](https://github.com/YenLinWu/Model_Drift#%E6%A8%A1%E5%9E%8B%E9%A3%84%E7%A7%BB-model-drift)
