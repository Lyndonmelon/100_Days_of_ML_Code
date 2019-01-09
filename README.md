# 100_Days_of_ML_Code
This is 100 days ML Code challenge, Wish me luck!!
This challenge is for me to reviewing what I've learned from Taiwan Artificial Inteligence Academy(AIA)
If there is any problem or mistake in the file, please comtact me, thank you.

這是100 days ML Code challenge，這個repository的目的是整理我在台灣人工智慧學校所學習的課程內容，以及我所搜集的資源。
若內容有任何錯誤，請一定要告知我，thanks!

Btw, this is the link of the vedio and github about the 100_Days_of_ML_Code:
https://github.com/llSourcell/100_Days_of_ML_Code
https://www.youtube.com/watch?v=cuQMBj1cWPo&t=7s

Challenge start from 2018/12/24.

### Day 1 | Data preprocessing (資料預處理）
[click me!!](https://github.com/Lyndonmelon/100_Days_of_ML_Code/tree/master/Day_1_data_preprocessing)

### Day 2 | Linear Regression (線性回歸）
[click me!!](https://github.com/Lyndonmelon/100_Days_of_ML_Code/tree/master/Day_2_linear_regression)

### Day 3 | Logistic Regression (邏輯回歸）
[click me!!](https://github.com/Lyndonmelon/100_Days_of_ML_Code/tree/master/Day_3_logistic_regression)

### Day 4 | Polynomial Regression (多項式回歸）
[click me!!](https://github.com/Lyndonmelon/100_Days_of_ML_Code/tree/master/Day_4_Polynomial_regression)

### Day 5 | Linear Model Selection and Regularization 
在先前幾天有複習到overfitting的問題，因此今天針對要如何選擇一個好的Model與相關的手法加以複習，複習的資源為：
1. [李宏毅老師課程 ML Lecture 2: Where does the error come from?](https://www.youtube.com/watch?v=D_S6y0Jm6dQ&t=1575s)
2. [An Introduction to Statistical Learning - 第六章](https://www.ime.unicamp.br/~dias/Intoduction%20to%20Statistical%20Learning.pdf)

### Day 6 | Project - Warm Up: Predict Blood Donations
https://www.drivendata.org/competitions/2/warm-up-predict-blood-donations/submissions/
第六天利用Drivendata網站上的項目來做練習。[Code](https://github.com/Lyndonmelon/100_Days_of_ML_Code/tree/master/Day_6_project)

### Day 7 | Support Vector Machine (reading)
今天複習SVM課程，SVM是機器學習中相當經典的一個演算法，此演算法經常拿來應用在分類問題中，但其實SVM也可以用來預測回歸的問題，其實不管是分類或回歸的問題，其實SVM就是在找一個最適平面去將資料分類，或是或是做準確的預測。相關資料：
1. [李宏毅老師課程 ML Lecture 20: Support Vector Machine (SVM)](https://www.youtube.com/watch?v=QSEPStBgwRQ&index=29&list=PLJV_el3uVTsPy9oCRY30oBPNLCo89yu49)
2. [Support Vector Machines 簡介](http://www.cmlab.csie.ntu.edu.tw/~cyy/learning/tutorials/SVM2.pdf)

### Day 8 | Support Vector Machine (reading+code)
學習資源:
1. [hands on machine learning with scikit-learn and tensorflow](https://github.com/ageron/handson-ml/blob/master/05_support_vector_machines.ipynb)

### Day 9 | Trees 決策樹 (reading)
學習資源：
1. [hands on machine learning with scikit-learn and tensorflow](https://github.com/ageron/handson-ml/blob/master/06_decision_trees.ipynb)
2. [hands on machine learning with scikit-learn and tensorflow](https://github.com/ageron/handson-ml/blob/master/07_ensemble_learning_and_random_forests.ipynb)
3. [資料分析&機器學習 第3.5講 : 決策樹(Decision Tree)以及隨機森林(Random Forest)介紹](https://medium.com/@yehjames/%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-%E7%AC%AC3-5%E8%AC%9B-%E6%B1%BA%E7%AD%96%E6%A8%B9-decision-tree-%E4%BB%A5%E5%8F%8A%E9%9A%A8%E6%A9%9F%E6%A3%AE%E6%9E%97-random-forest-%E4%BB%8B%E7%B4%B9-7079b0ddfbda)
4. [資料分析&機器學習 第5.2講: Kaggle機器學習競賽神器XGBoost介紹](https://medium.com/@yehjames/%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-%E7%AC%AC5-2%E8%AC%9B-kaggle%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92%E7%AB%B6%E8%B3%BD%E7%A5%9E%E5%99%A8xgboost%E4%BB%8B%E7%B4%B9-1c8f55cffcc)

(打算先將一些手邊資源先複習完，後續code的部分在以project的形式練習）
### Day 10 | PCA 降維 （reading)
PCA降維是在機器學習中非常重要的技巧，原因是通常取得的資料維度都相當高，雖然說也可以選擇在做完EDA+datapreprocessing後就直接測試模型，但是將資料做好的降維處理會幫助你加速後續模型的訓練、減少不必要的維度，甚至是可以做視覺化（前提是在三維以下，同時也有encoder的效果；但降維並不是只有優點，若資料集維度高且大，做資料降維計算時間可能會拉長，導致整個ML pipline的複雜度，而且將為後的特徵也很難解釋。因此如何降維，要降到幾維？便是一個很值得學習的問題。學習資源：

1. [hands on machine learning with scikit-learn and tensorflow](https://github.com/ageron/handson-ml/blob/master/08_dimensionality_reduction.ipynb)
2. [李宏毅老師課程 ML Lecture 16: Unsupervised Learning - Auto-encoder](https://www.youtube.com/watch?v=Tk5B4seA-AU&list=PLJV_el3uVTsPy9oCRY30oBPNLCo89yu49&index=25)

### Day 11 | Naive Bayesian Classifier & Hidden Markov Model
簡單貝氏分類器（Naive Bayesian Classifier)以及隱馬可夫模型（Hidden Markov Model)都是透過機率來解決像是分類、語音辨識、機器翻譯等問題，兩者都是不複雜的數學模型。

（１）簡單貝氏分類模型其實就是建立在條件機率上的一個模型，透過『獨立事件假設』前提來計算事件機率，也就是在每一維的資料都是獨立的前提下，進行計算做出分類，這是此模型的特點也是不太符合現實情況的一個地方，因為現實的資料可能不會滿足這個假設，就像是我們說出「豆漿」這個詞接續的比較可能是「油條」而不是「巧克力」一樣的道理。相關資源如下：
1. [AI - Ch15 機器學習(3), 樸素貝葉斯分類器 Naive Bayes classifier](http://mropengate.blogspot.com/2015/06/ai-ch14-3-naive-bayes-classifier.html)
2. [初探機器學習使用python](https://www.books.com.tw/products/0010764445)

（２）隱馬可夫模型是基於馬可夫鏈所發展出的模型，馬可夫鍊的假設為「在隨機過程中，各個狀態S_t的機率分佈，只與他的前一個狀態S_t-1有關」，因此我們即可以利用這個假設來知道我們在某個狀態m_i到m_j的移轉機率。而隱馬可夫模型就是馬可夫鍊的一個延伸：模型中任意時間t的狀態S_t是不可見的，所以觀察者無法透過觀察一個狀態序列來推測狀態移轉的機率，但是HMMs(隱馬可夫模型)在每個時刻t都會輸出一個輸出項O_t而且這個O_t跟S_t相關且僅跟S_t相關，透過此輸出項與狀態的關係推算出實際模型中各時間狀態移轉的機率」。利用隱馬可夫模型的這個特性，此模型就可以利用在自然語言處理中的翻譯、語音辨識、文字偵錯等問題上。相關資源如下：
1. [CS188 Lecture 18 HMMs](https://www.youtube.com/watch?v=9dp4whVQv5s)
2. [數學之美 ch.5](https://www.tenlong.com.tw/products/9787115373557)

### Day 12 | T_brain資料競賽-玉山人工智慧公開挑戰賽#1 - 金融商品交易預測 (project)
[競賽連結](https://tbrain.trendmicro.com.tw/Competitions/Details/5)
Data Preprocessing.

### Day 13 | T_brain資料競賽-玉山人工智慧公開挑戰賽#1 - 金融商品交易預測 (project)
Data preprocessing.

### Day 14 | 複習深度學習訓練方法與Tensorflow
深度學習神經網路訓練通常會碰到很多問題，不管是overfitting或是underfitting，要如何針對訓練情況對症下藥調整超參數是非常重要的，而使用其他的技巧如early stopping、regularization或者是dropout也非常的關鍵，那在了解了其中的方法，要如何在程式上實現，又是另一個問題了。深度學習使用的框架也是很多種，例如Tensorflow、pytorch等等，因為在AIA學習的是tensorflow，因此將針對tensorflow來複習。
1. [Hands on machine learning on sci-kitlearn nad tensorflow](https://github.com/ageron/handson-ml/blob/master/11_deep_learning.ipynb)
2. [李宏毅老師課程 ML Lecture 9-1: Tips for Training DNN](https://www.youtube.com/watch?v=xki61j7z-30&list=PLJV_el3uVTsPy9oCRY30oBPNLCo89yu49&index=16)

### Day 15 |  CNN學習與實作
CNN(Convolutional Neural Neework)是類神經網路的一種，為人所知的就是他在影像上的處理，但是其實CNN可以拿來應用在不同的問題上，如時間序列問題等，其衍伸的型態還有很多種，而本次將利用MNIST資料集來實作建構一個Siamese Neural Network。相關學習資源：
1. [Hands on machine learning on sci-kitlearn nad tensorflow](https://github.com/ageron/handson-ml/blob/master/13_convolutional_neural_networks.ipynb)
2. [What are Siamese neural networks, what applications are they good for, and why?
](https://www.quora.com/What-are-Siamese-neural-networks-what-applications-are-they-good-for-and-why
3. [Neural Networks - Siamese Network](https://www.youtube.com/watch?v=AKyHGzCSEK4)

### Day 16 |  CNN學習與實作
實際練習建構Siamese Neural Network
[Siamese Neural Network](https://github.com/Lyndonmelon/100_Days_of_ML_Code/blob/master/Day_15_DNN/Day_15_DNN.ipynb)
1. [Dimensionality Reduction by Learning an Invariant Mapping](http://yann.lecun.com/exdb/publis/pdf/hadsell-chopra-lecun-06.pdf)

### Day 17 |  影像辨識文獻reading-day1
影像辨識其實是深度學習中很重要的一個問題，因為目前AIA期末專案是做物件辨識，因此針對相關文獻與文章進行學習，又因為影像辨識問題所提出的 model相當多（如R-CNN, Faster R-CNN, Yolo等），將規劃三天研讀此主題。相關文獻資料如下：
1. [Understanding the mAP Evaluation Metric for Object Detection](https://medium.com/@timothycarlen/understanding-the-map-evaluation-metric-for-object-detection-a07fe6962cf3)相當重要的一篇
2. [一文读懂：R-CNN、Fast R-CNN、Faster R-CNN、YOLO、SSD](https://hk.saowen.com/a/ea0b8f4a0266432ae2df9b75548929b77393a26141d06a70f8a3061025462b77)
3. 其他paper則不一一列出，相關連結皆有在上面兩篇文章中。



