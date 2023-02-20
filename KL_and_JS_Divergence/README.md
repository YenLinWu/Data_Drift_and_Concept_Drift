# Kullback-Leibler Divergence & Jensen-Shannon Divergence  
> 吳彥霖 [![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yenlinwu/)   on February 20, 2023   

在監控模型飄移(Model Drift)的方法中， KL 散度(Kullback-Leibler Divergence)與 JS 散度(Jensen-Shannon Divergence)可用來偵測是否發生資料飄移(Data Drift)，兩者都是以信息熵(Information Entropy)為基礎做定義，皆可作為度量兩個機率分佈 P 與 Q 相似度的一種統計距離(Statistical Distance)。兩者最大的差別在於， KL 散度不具有距離尺度的對稱性(Symmetric)， KL 散度不為距離尺度，然而， JS 散度彌補了 KL 散度的對稱性且為一距離尺度。  

## Python 程式碼範例  
> Requirements : ![Python](https://img.shields.io/badge/Python-3.8.10-blue.svg) ![Numpy](https://img.shields.io/badge/NumPy-1.21.6-range.svg) ![Pandas](https://img.shields.io/badge/Pandas-1.3.5-range.svg) ![Matplotlib](https://img.shields.io/badge/Matplolib-3.2.2-range.svg) ![SciPy](https://img.shields.io/badge/SciPy-1.7.3-range.svg)    

[![Colab](https://img.shields.io/badge/Python_Script-Google_Colab-yellow.svg)](https://colab.research.google.com/github/YenLinWu/Model_Drift/blob/dev/KL_and_JS_Divergence/KL_and_JS_Divergence.ipynb)  :point_left:

<p align="left">
<img width="550" src="https://raw.githubusercontent.com/YenLinWu/Model_Drift/dev/KL_and_JS_Divergence/Imgs/Data_Shift_Detection_in_KL_and_JS_Divergence.gif">
</p>

Back to [How to Detect Model Drift?](https://github.com/YenLinWu/Model_Drift/tree/dev#%E6%A8%A1%E5%9E%8B%E9%A3%84%E7%A7%BB-model-drift)
