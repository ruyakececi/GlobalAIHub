Giriş
Merhaba,
Bu projede kestirimci bakım alanında, endüstriyel bir makinada, makina sensörlerinden gelen veriler doğrultusunda makinanın hata verme sonuçlarını içeren dataset ile çalışıldı.
Dataset kaggledan alınmıştır, linki:
https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification


Metrikler
Makinemi sensörlerden gelen sıcaklık, tork, hız gibi veriler aracılığıyla hata tahmini için eğittim.
Bir classification problemi olarak targetım makina çalışması sırasında 'hata alacak (1)/ hatasız (0)' sonucunu tahmin etmek üzere kurgulanmıştır. 
Yaptığım train ve test işlemleri sonucunda denediğim modellerde Random Forest en yüksek sonucu verdi ve projemi bu model ile sonlandırdım.

Sensör verileri imbalanced olduğunu gözlemledim. 
Datasetimde hata almayan verilerin sayıca çok olduğu grafiklerden akunuyordu. 
SMOTE kütüphanesini kullanarak verileri dengelemeye çalıştım fakat hata ile karşılaştım. Proje bitirme gününe denk geldiğim için bu şekilde sunma kararı aldım. 
Sunduğum projemde verisetim Confix matriksinde de görüldüğü gibi TP iyi eğitilmiştir.  


Sonuç ve Gelecek Çalışmalar
Bundan sonra yapılacaklar görevlerim,
Dataset balance
Arayüz olarak dashboard hazrılamak,
Gerçek bir makina verileri toplayıp proje denemek.


Linkler
Çalışmama ait tüm Kaggle linki:
https://www.kaggle.com/code/ryakeeci/machine-predictive-maintenance-classification
