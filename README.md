# Predict-Dollar
  Bu projemde doların bir zaman dilimi içerisinde tl karşılığı bulanan .csv dosyasının içindeki verileri kullanarak tahmin işlemi gerçekleştirdim. 
  Öncelikle verileri matplotlib kütüphanesini kullanarak görüntüledim.
  
  ![alt text](https://github.com/MelisaYasak/Predict-Dollar/blob/main/dollar1.png?raw=true)
  
  Linear Regresyon() kullanarak veriyi eğittim daha sonra tekrar matplotlib kütüphanesini kullanarak tahmin edilen değer ile gerçek değeri çizdirdim ve sklearn kütüphanesinden mean squared error metric ile doğruluk hesabı yaptırdım. 
  
  
  ![alt text](https://github.com/MelisaYasak/Predict-Dollar/blob/main/dollar2.png?raw=true)
  
  Daha sonra grafiğin polinamal regresyona uyabileceğini düşünüp aynı veri setini Polinamal regresyonla tahmin ettirdim ve matplotlib ile tekrar çizdirdim ve sklearn kütüphanesinden mean squared error metric ile doğruluk hesabı yaptırdım.
  
  ![alt text](https://github.com/MelisaYasak/Predict-Dollar/blob/main/dollar3.png?raw=true)
  
  Gördüm ki polinomal Regresyona daha uygunmuş.
