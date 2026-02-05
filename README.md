# Line-Follower-Robot
İstanbul Gelişim Üniversitesi bünyesinde hazırlanan, Arduino ve L298N motor sürücü kullanan otonom çizgi izleyen robot projesi
Çizgi İzleyen Robot (Line Follower Robot) Bu proje, otonom bir şekilde yerdeki siyah/beyaz çizgiyi takip ederek belirli bir rotada ilerleyen bir robot sistemidir. Proje, özellikle endüstriyel alanlarda ve depolarda yük taşıma işlemlerini otomatikleştirmek amacıyla tasarlanmıştır.
Teknik Özellikler Robot, zemin üzerindeki çizgiyi IR sensörler aracılığıyla algılar ve Arduino mikrodenetleyicisi sayesinde tekerlek motorlarını kontrol eder.
Mikrodenetleyici: Arduino Uno Motor Sürücü: L298N Modülü Sensörler: IR (Kızılötesi) Sensör Modülleri Güç Kaynağı: Pil yatağı ve piller
 Proje Görselleri:çizgi izleyen robot görsel.jpeg  çizgi izleyen robot projesi.jpeg 
 Çalışma MantığıSistem, IR sensörlerden gelen yansıma verilerini (0 ve 1) işleyerek yönünü belirler:Sensör DurumuHareket KararıOrta sensör "0", Sağ ve Sol "1"Düz İlerle Sağ sensör "0", Diğerleri "1"Sağa Dön Sol sensör "0", Diğerleri "1"Sola Dön 
