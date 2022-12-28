# Derin-Orenme
CNN ile İşaret Dili Tanıma
Bu çalışmada American Sign Language veri seti kullanılmıştır. American Sign 
Language veri seti ise 36 farklı sınıf ve 2515 görüntüden oluşmaktadır. Veri seri üzerinde 
öncelikli olarak veri ön işleme adımları gerçekleştirilecektir. Bu işlemler ile modelin 
alacağı girdinin modele en uygun hale getirilmesi amaçlanmaktadır. Bu projede verilerin
algılanarak yazıya çevrilmesini sağlamak için Konvolüsyonel Yapay Ağlar (Convolutıion 
Neural Network) derin öğrenme tekniği kullanılmıştır. Proje için derin öğrenme 
algoritmalarından olan CNN tekniğinin seçilme nedeni klasik makine öğrenmesi 
algoritmalarından farklı olarak öznitelik çıkartma işleminin de algoritma ile yapılması ve 
veri özniteliklerinin çıkartılmasında insana ihtiyaç duyulmamasıdır. CNN genellikle 
görüntü işlemede kullanılan ve girdi olarak görselleri alan bir derin öğrenme 
algoritmasıdır. Farklı operasyonlarla görsellerdeki featureları (özellikleri) yakalayan ve 
onları sınıflandıran bu algoritma farklı katmanlardan oluşmaktadır. Konvolüsyonel Yapay 
Ağlarına (CNN) verilen girişler, her değeri 0- 255 arasında değişen bir piksel değerleri 
dizisidir. Bir görüntü üç renk kanalından oluşmaktadır. Bu üç kanal Red, Green, Blue 
(RGB) olarak adlandırılır ve kırmızı, yeşil ve mavi yoğunluğunu temsil eder. Görüntü 
sınıflandırma durumunda, CNN'in işi, bu görüntüyü, yani bir piksel değerleri dizisini, bir 
girdi olarak almak ve belirli bir sınıfa ait olma ihtimallerini çıkarmaktadır. Tahmin 
problemlerinde ise, model girdi olarak piksel değerlerini alır ve karşılık gelen çıktı 
değerlerini tahmin eder.
Yapay zekâ sınıflandırma uygulamalarında sonucun başarısı doğruluk, kesinlik, 
hassasiyet gibi parametreler ile ölçülmektedir. CNN algoritması, 100 epoch ile 
eğitildiğinde precision: 0.8486, recall: 0.7384, accuracy: 0.7912, validation loss: 0.1786, 
validation precision: 0.9073, validation recall: 0.8964 ve validation accuracy: 0.9004
değerleri elde edilmiştir. 
