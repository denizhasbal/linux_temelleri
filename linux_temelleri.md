#Linux Temelleri
 
##Terminal komutları (ls,cd,grep,mkdir,chmod,top)
   Terminal, bilgisayara yazarak komut vermemizi sağlar.

ls → Bulunduğun klasördeki dosyaları gösterir.
cd → Klasör değiştirir.
mkdir → Yeni klasör oluşturur.
grep → Bir metin içinde istediğin kelimeyi arar.
chmod → Dosyanın izinlerini değiştirir.
top → Çalışan işlemleri ve CPU/RAM kullanımını gösterir.


##Paket Yönetimi Nedir

 Linux'ta programları kurmak, güncellemek ve kaldırmak için paket yöneticileri kullanılır.

Dağıtıma göre farklı olabilir:

Ubuntu/Debian → apt
Arch → pacman
Fedora → dnf

Paket yöneticisi = Programları yönetmemizi sağlayan araç.


##Dosya İzinleri

     Linux'ta her dosyanın kim tarafından okunabileceği, değiştirilebileceği veya çalıştırılabileceği belirlenebilir.

Temel izinler:

r → read → okuma
w → write → yazma/değiştirme
x → execute → çalıştırma


##Servisler Ve Systemctl

    Servis, bilgisayar arka planda çalışan bir sistem hizmetidir.

      örn:
          Web sunucusu
          SSH
		  Veritabanı
