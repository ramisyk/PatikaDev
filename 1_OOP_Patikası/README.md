# Object Oriented Programming

## Ödev1 - Üniversite Yönetim Sistemi

.Net Patikası kapsamında başlamış olduğum OOP Modülünün ilk ödevi olan Üniversite Yönetim Sisteminin UML diyagramı aşağıdaki görseldeki gibidir.

Bu sistem için belirtilen isterler:
- Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.
- Departmanlara ait ofisler vardır.
- Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.
- Her çalışan bir ofiste çalışır.

![Uni Yonetim UML](https://github.com/ramisyk/PatikaDev/blob/master/1_OOP_Patikas%C4%B1/Ekler/universite_yonetim_uml.png)

##Ödev2 - Hayvanat Bahçesi

OOP ilkelerini kullanarak hazırlanan Hayvanat bahçesinin UML görseldeki, isterleri ve açıklamaları aşağıdakiler gibidir.

Hayvanlar:
-Atlar (atlar, zebralar, eşekler vb.),
-Kedigiller (kaplanlar, aslanlar vb.),
-Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
-Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
--tür adı, ağırlığı, yaşı vb.
-Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
-Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Nitelik ve methodları ortak olan türler için base bir "Hayvan" sınıfı oluşturulmuştur ve ortak olan bütün bilgiler bu sınıfta tanımlanmıştır. Method içerikleri değişiklik gösterileceği için aynı metodlar override yapılabilecek şekilde kendi türlerine ait sınıflarda yeniden yazılmıştır, içeriği uygun olarak doldurulacaktır. 

![Hayvanat Bahçesi UML](https://github.com/ramisyk/PatikaDev/blob/master/1_OOP_Patikas%C4%B1/Ekler/universite_yonetim_uml.png)
