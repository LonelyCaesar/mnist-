# mnist-Handwritten-digit-recognition
# 一、說明
深度學習就是透過各種類神經網路，本專題會使用多層感知器(MLP)、卷積神經網路(CNN)、循環神經網路(RNN)透過mnist資料集產出訓練出來的值，將一大堆的數據輸入神經網路中，讓電腦透過大量數據的訓練找出規律自動學習，最後讓電腦能依據自動學習累積的經驗作出預測。

# 二、相關文章
多層感知器(MLP)：多層感知器是由多層人工神經元組成的類神經網路, 在 MINST 資料集的手寫數字辨識中要用到的 MLP 為如下具有輸入層, 一個隱藏層, 以及輸出層的類神經網路。
![image](https://github.com/LonelyCaesar/mnist-Handwritten-digit-recognition/assets/101235367/e6df9c0a-662d-4f9b-8b25-0c586c6fdbf9)

為了提高學習的準確率，神經網路更發展到有一個輸入層、一個或多個隱藏層及一個輸出層的多層感知器(MLP)。

輸入層：數字圖片是一張28*28的圖片、共有784個神經元所組成了神經網路第一層，數值的範圍介於0~1之間。灰階0代表灰色、1代表白色，又稱為激勵值，數值越大則該神經元就越亮。

輸出層：完成輸入層後先不管其他層的內容，我們來看看他最右方的輸入層，也就是最後判斷的結果，其中有10個神經元，各代表數字0~9，其中也有代表的激勵值。

隱藏層：為了方便說明，在這裡我們設計了兩個隱藏層，每層有16個神經元。在真實的案例中可依據需求設置調整隱藏層與神經元的數量。

卷積神經網路(CNN)：它是目前深度神經網路(Deep Neural Network)領域發展的主力，在圖片辨別上甚至可以做到比人類還精準之程度。


