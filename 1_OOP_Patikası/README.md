# Object Oriented Programming

## Ödev1 - Üniversite Yönetim Sistemi

.Net Patikası kapsamında başlamış olduğum OOP Modülünün ilk ödevi olan Üniversite Yönetim Sisteminin UML diyagramı aşağıdaki görseldeki gibidir.

Bu sistem için belirtilen isterler:
- Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.
- Departmanlara ait ofisler vardır.
- Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.
- Her çalışan bir ofiste çalışır.

![Uni Yonetim UML](https://github.com/ramisyk/PatikaDev/blob/master/1_OOP_Patikas%C4%B1/Ekler/universite_yonetim_uml.png)

## Ödev2 - Hayvanat Bahçesi

OOP ilkelerini kullanarak hazırlanan Hayvanat bahçesinin UML'i görseldeki, isterleri ve açıklamaları aşağıdakiler gibidir.

Hayvanlar:
- Atlar (atlar, zebralar, eşekler vb.),
- Kedigiller (kaplanlar, aslanlar vb.),
- Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
  - tür adı, ağırlığı, yaşı vb.
- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
- Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Nitelik ve methodları ortak olan türler için base bir "Hayvan" sınıfı oluşturulmuştur ve ortak olan bütün bilgiler bu sınıfta tanımlanmıştır. Method içerikleri değişiklik gösterileceği için aynı metodlar override yapılabilecek şekilde kendi türlerine ait sınıflarda yeniden yazılmıştır, içeriği uygun olarak doldurulacaktır. 

![Hayvanat Bahçesi UML](https://github.com/ramisyk/PatikaDev/blob/master/1_OOP_Patikas%C4%B1/Ekler/hayvanat_bahcesi_uml.png)

## Ödev3 - Uçuş Yönetim Sistemi

OOP ilkelerini kullanarak hazırlanan Uçuş Yönetiminin UML'i görseldeki, isterleri ve açıklamaları aşağıdakiler gibidir.

- Hava yolu şirketleri uçuşları gerçekleştirir. Her hava yolunun bir kimliği vardır.
- Hava yolu şirketi, farklı tipteki uçaklara sahiptir.
- Uçaklar çalışır veya onarım durumunda olabilir.
- Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.
- Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.
- Havaalanlarının benzersiz kimlikleri ve isimleri vardır.
- Hava yolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.
- Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.

Soyutlamayı ve kalıtımları tam olarak yapabilmek için base sınıflar ve onun alt sınıfları oluşturulmuştur. Havayolu şirketi Pilot, Uçak ve Uçuş bilgilerini tutmaktadır o sınıfları altında barındırmaktadır. Havaalanı Uçuşları kontrol etmelidir.

![Ucus Yonetim Sistemi](https://github.com/ramisyk/PatikaDev/blob/master/1_OOP_Patikas%C4%B1/Ekler/havayolu_yonetim_uml.png)

## Ödev4 - Online Film Sistemi

OOP ilkelerini kullanarak hazırlanan film satın almaya ve kiralamaya imkan sunan Online Film Sisteminin UML'i görseldeki, isterleri ve açıklamaları aşağıdakiler gibidir.

- Uygulamada filmler listelenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.
- Kullanıcılar abonelik için sistem üzerinden kredi satın alır.
- Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.
- Normal kullanıcılar ve aboneler film satın alabilirler.
- Eğer film mevcut değil ise talep edilebilir.

![Online Film Sistemi](https://github.com/ramisyk/PatikaDev/blob/master/1_OOP_Patikas%C4%B1/Ekler/film-kiralama-uml.png)
