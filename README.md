# Predict-Dollar
  Bu projemde doların bir zaman dilimi içerisinde tl karşılığı bulanan .csv dosyasının içindeki verileri kullanarak tahmin işlemi gerçekleştirdim.
  
  In this project, I made an estimation using the data in the .csv file, which was found in TL equivalent of the dollar in a time period.
  
  Öncelikle verileri matplotlib kütüphanesini kullanarak görüntüledim.
  
  First, I displayed the data using the matplotlib library.
  
  ![alt text](https://github.com/MelisaYasak/Predict-Dollar/blob/main/dollar1.png?raw=true)
  
  Linear Regresyon() kullanarak veriyi eğittim daha sonra tekrar matplotlib kütüphanesini kullanarak tahmin edilen değer ile gerçek değeri çizdirdim ve sklearn kütüphanesinden mean squared error metric ile doğruluk hesabı yaptırdım.
  
  I trained the data using Linear Regression(), then again plotted the estimated value and the actual value using the matplotlib library, and calculated the accuracy with the mean squared error metric from the sklearn library.
    
  ![alt text](https://github.com/MelisaYasak/Predict-Dollar/blob/main/dollar2.png?raw=true)
  
  Lineer Regresyon() ile 300. gün tahmini yaptırdım.

  I made a 300th day estimation with Linear Regression().
  
  Daha sonra grafiğin polinamal regresyona uyabileceğini düşünüp aynı veri setini Polinamal regresyonla tahmin ettirdim ve matplotlib ile tekrar çizdirdim ve sklearn kütüphanesinden mean squared error metric ile doğruluk hesabı yaptırdım.
  
  Then, thinking that the graph could fit the polynomial regression, I estimated the same data set with Polynamal regression and re-plot it with matplotlib and calculated accuracy with the mean squared error metric from the sklearn library.
  
  ![alt text](https://github.com/MelisaYasak/Predict-Dollar/blob/main/dollar3.png?raw=true)
  
  Gördüm ki polinomal Regresyona daha uygunmuş.
  
  I saw that it is more suitable for polynomial regression.
  
  Polinomal Regresyon ile 300. gün tahmini yaptırdım.

  I made a 300th day estimation with Linear Regression().
