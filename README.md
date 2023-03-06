# Python ile MongoDB

<h2>Kütüphane Kurulumu Hakkında</h2></br>
Gerekli kütüphane: pymongo


<span style="color: blue">pip install </span> pymongo

komutu ile kütüphaneyi eklemeyi başaramadıysanız aşağıdaki linkten pymongo kütüphanesini manuel olarak indiriniz.
Ve python kodlarınız bilgisayarınızda hangi klasör içindeyse (örn: C:\Users\tokel ) o konuma kütüphane dosyasını ekleyiniz.

Link: https://pypi.org/project/pymongo/#files

</br></br>

<h2>Uygulamanın MongoDB'ye Bağlanması Hakkında</h2></br>

![MongoClient](https://user-images.githubusercontent.com/102792446/223052839-bb052797-52d5-40a5-b3c9-6188c79de7f1.png)

Yukarıda sarı renkle işaretlenmiş kısımları doldururken **MongoDB içinde veritabanınız için oluşturduğunuz admin username ve admin password** ü kullanınız.

</br></br>

**Örnek:** 
Veritabanınız için oluşturduğunuz 
admin username = **karsudonmez** <br/>
admin password = **amsterdam123**
ise
![image](https://user-images.githubusercontent.com/102792446/223054668-6e9afc42-9980-432e-977c-062a1c02990f.png)


Kodlarınız aşağıdaki gibi olmalıdır:
![Ekran görüntüsü 2023-03-06 111343](https://user-images.githubusercontent.com/102792446/223054293-5f851f5a-820d-4372-9848-76a6d28b3a2e.png)
