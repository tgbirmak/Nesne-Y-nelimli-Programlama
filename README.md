
# Nesne yönelimli programlama notları

- Objeler: Name, attributes, behaviors -- isim, nitelik, davranış olarak objeler değerlendirilir.

- Birleşik Programlama Modeli : UML (Unified Modeling Language) Ekiplerin UML diyagramları farklıdır. Konuya göre diyagramlar değişiklik göstermektedir.

# **SINIF VE NESNE KAVRAMLARI**
 
# *Nitelikler (Değişkenler)*


### + name : String ---> + public, -private, #  protected , Niteliğin ismi ve veri tipi.

görünürlük, isim, veritipi, varsayılan değer

# *Davranışlar (Metotlar)*

## Görünürlük (Visibility)
## İsim(Name)
## Parametre Listesi (Parameter List)
## Geri Dönüş Türü (Return Type)

..+ showMoney() : void
..- sendMoney() : bool
.. # withDraw(int amount) : bool
# **UML ve SINIF Diyagramları**

## Modelleme ve Soyutlama - Modelling and Abstraction
## UML (Unified Modeling Language) Nedir?
-     Birleşik Programlama Modeli : UML (Unified Modeling Language) Ekiplerin UML diyagramları farklıdır. Konuya göre diyagramlar değişiklik göstermektedir.
- Hataları indirgeme
- Kodlama kolaylığı
- Tekrar kod engelleme
- Mantıksal hataları indirgeme
- Geliştirme maliyeti azalımı
- Resmin bütün görünnmesi
- UML diyagramları ile verimli bellek kullanımı
- Karmaşık sistemlerde değişiklik
- UML ile dökümanlaştırılmış kodları düzenlemek
- UML diyagramını kullananların aynı dili konuşması

# **Sınıflar Arası İlişkiler**

- Bağlantı İlişkisi (Association)
- Genelleme/Kalıtım İlişkisi (Generalization/Inheritance)
- Bağımlılık İlişkisi (Dependency)(Aggregation, Composition)
- Gerçekleştirim İlişkisi (Realization)
 
 ## *Association Class*
 
 "Müşteri" -- "Ürün" -- "Sipariş" sınıfları arasındaki ilişki :: "satın alma"

Bir sınıf, n tane başka bir sınıf ile ilişki ;

Bir "sepet" sınıfına birden fazla "ürün" gelebilir. "1"----***

Bire bir, bire çok, çoka bir, bire sıfır, bire beş bire sekiz

## *Reflexive Associations*

Bir sınıfın birden fazla rolü varsa ortaya çıkar.

Banka müşterisi, diğer banka müşterisine para gönderebiliyor. Kendi kendine ilişki.
Bir banka müşterisi başka bir veya birden fazla müşteriye para gönderebilir. 1 ----1 .. ***
## *Kalıtım (Inheritance) ve Genelleme (Generalization) İlişkisi*

Kalıtım örneği; "Kare" subclassı "Şekiller" classından bütün özellikleri alır. (Genetik olarak gelir) (Extends)

### "Araba" nesnesi ürettiğimizde, "motor", "koltuk", "lastik" nesnelerinin üretilmesini bekliyoruz.
1 araba : 1 motor 5 koltuk 4 lastik gibi.

elmas boş olduğunda "içerme", dolu olduğunda "oluşma" ilişkisi.

oluşma (composite) ilişkisi : bütün parça en yukarda olacak.

## *Gerçekleştirim (Realization) İlişkisi*

Kişiler adında interface oluşturduğumuzda (user interface) Öğrenci, Öğretmen, Asistan subclasslarına dağılıyor.
Kişilerde adSoyad String, fakat değer almıyor.
Öğrencinin "adSoyad" değeri olmak zorunda.



