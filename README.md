# Python---Book-Reader

Bilgisayarda bulunan bir Pdf dosyasının sesli bir şekilde okutulması hedeflendi. Benzer programlar
incelendi ve gerekli kütüphaneler indirilerek komut ekranından bilgisayara kuruldu. Programda iki 
tane kütüphane kullanıldı. Bunlar “pyttsx3” ile “PyPDF2” kütüphaneleridir. “pyttsx3” kütüphanesi, 
gerekli kod ayarlamaları yapılarak bir metnin sesli okutulmasını sağlamaktadır. İkinci kütüphane olan 
“PyPDF2” ile bir Pdf dosyası üzerinde işlem yapılabilmektedir. Kütüphanelerden sonra okutulmak 
istenen Pdf dosyasının konumu belirtilerek read-binary modunda dosya açıldı ve ‘hikaye’ adlı
değişkene atandı. Metin okuyucu kütüphanesinin başlatma komutu yazılarak sesli okuyucu başlatıldı
ve ayar komutu ile sesin ayarlarına geçildi. Seste cinsiyet ayarı yapıldı. Kütüphanede tanımlı olan iki 
ses ayarı vardır. Bunlar kadın ve erkek sesi. Kadın sesi için id=0 değeri, erkek sesi için id=1 değeri kod 
içerisinde ayarlanarak iki farklı seçenekte metin okutulabilir.
Bu programda kod içerisinde bilgisayardaki konumu belirtilen bir Pdf dosyasındaki yazı, program 
tarafından sesli bir şekilde okutuldu. Ses türü kadın veya erkek sesi olarak kod içerisinde 
değiştirilebilmektedir. Kodlama tamamlandığında programa “Management-basics” adlı bir sayfalık bir 
Pdf dosyası erkek ve kadın sesi için ayrı ayrı okutuldu.
