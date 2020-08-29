# ML Image Recognition

1.OpenCV
    1)图像尺寸(.shape)
    图像的大小可以通过其shape属性来获取，shape返回的是一个tuple元组，第一个元素表示图像的高度，第二个表示图像的宽度，第三个表示像素的通道数(BGR)。
    2)Filter ⼜又稱做 kernel，概念念上是⼀一個固定⼤大⼩小的矩陣，掃過圖片經過計算後取得新的圖片矩陣
    3)模糊 - Averaging, Gaussian Blur
    最簡單的概念念是只要把周遭的 pixel 全部平均就好但比較常使⽤用的是 Gaussian Filter，認為中⼼心點的資訊還是最重要的
    4)Filter 的操作
    了解計算圖片的導數就會取得邊緣在電腦視覺中我們也可以把這個過程稱為「抽取特徵」所謂特徵，可以非常直覺的解釋為「圖片中最特別的地⽅方」可以是邊緣，輪輪廓，紋理理等資訊
    5)Feature Matching - ratio test
    根據補充資料的論⽂文提到建議比值設定在 0.7~0.8 比較好