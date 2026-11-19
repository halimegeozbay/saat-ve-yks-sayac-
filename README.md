# Saat ve YKS Sayacı

Aslında kendim için yaptığım ama yine de paylaşmak istediğim uygulama.
Uygulama oldukça temel olmakla beraber gerçekleştirebildiği 3 tane vasfı var:
1) Güncel tarihi göstermek,
2) Güncel saat, dakika ve saniye bilgisini göstermek
3) Seçilen YKS oturumuna kaç gün, saat, dakika kaldığını göstermek.

## Kurulumu

Verilen .zip dosyası indirilir, rar'dan çıkarılır.
.exe dosyası çalıştırılır.

## Kullanımı

F11 veya Tam ekran düğmesi: tam ekranı açar/kapatır.
Esc: tam ekrandan çıkar.
Saniye: normal saatin saniyesini gösterir/gizler.
Oturum seçimi: sıradaki oturum, TYT veya AYT.

Oturum ve saniye tercihlerin sonraki açılış için kaydedilir.
Uygulama internet olmadan çalışır. Windows'un .NET Framework bileşenini kullanır.
Pencere küçültüldüğünde saat güncellemeleri durur, geri açıldığında güncel saati gösterir.

TYT 19 Haziran 2027, AYT 20 Haziran 2027 olarak ayarlı. Başlangıç saati 10.15 varsayılmıştır.
Sınav tarihleri Türkiye saatiyle hesaplanır. Normal saat bilgisayarının saatidir.

Kaynak klasöründeki C# kodu ve Build.ps1, uygulamayı yeniden derlemek içindir.

