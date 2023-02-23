# AkbilYonetimi_SUNUM
Merhaba, Akbil Yönetimi Projesini İstanbul - Beşiktaş Wissen Akademi'de Kursiyerlik yaptığım süreçte oluşturduk. Akbil Yönetimi Projesi mevcuttaki İBB'nin uygulamasından esinlenilerek yazdığımız bir masaüstü projedir. İBB'nin çok kapsamlı bir projesini yakınsamak istedik ancak belirli kurs sürecimizdeki zaman koşullarına göre yazdık. Bu proje ile amacımız gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

* Proje .NET C# Windows Form yapısıyla yazılmıştır.

* Proje Visual Studio 2019 IDE'sinde yazılmıştır.

* Projede bulunan kayıtlar Microsoft Sql Server Management Studio 2019 veritabanı kullanarak kaydedilmiştir.

* Proje Entity Framework DBFirst-Database First yaklaşımıyla yazılmıştır.

* Projede üye olurken şifreler MD5 ile veri tabanına kaydedilmiştir.

* Beni hatırla butonu ile giriş yapan son kullanıcının bilgileri kayıt olmaktadır. Tekrar girerken kolayca sisteme girebilir.

* Projeyi 2 katman (DAL,UIForm) olarak yazılmıştır.

*Projede Akbil ekleme, talimat ekleme, ayarlar ve ana ekran sayfası bulunmaktadır.
* Üye sisteme giriş yaptıktan aşağıdaki adımları izleyerek akbile talimat ekleyebilir.

Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.

Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz.
Giriş yaptığımızda bizi karşılayan sayfamız;
![image](https://user-images.githubusercontent.com/73429501/220537634-8af2eea0-b36d-4d1b-a816-eacb22e9a965.png)

Akbil işlemlerini gerçekleştirmemiz için kayıt oluşturmalıyız. Kayıt olma sayfamıza bilgilerimizi girerek kayıt oluyoruz.
![kayıt olma](https://user-images.githubusercontent.com/73429501/220538492-cddebbb4-d6b7-458a-bbc9-b322ac2567ca.JPG)

Daha sonra Giriş yap sayfasına dönerek bilgilerimizi girerek giriş yapıyoruz. Beni hatırla butonu ile sistemin bilgilerimizi kaydederek hatırlamasını sağlayabiliriz.
![image](https://user-images.githubusercontent.com/73429501/220538910-2e78ad61-76cc-4ebd-8d1a-e2ad16a8ab5c.png)

Giriş yapıldıktan sonra ekranda Hoşgeldiniz yazısı ile karşılaşarak akbil işlemleri sayfasına yönlendirildik buradan hangi işlemi yapmak istediğimizi seçiyoruz.
![image](https://user-images.githubusercontent.com/73429501/220539266-25c3492c-a8be-416e-be60-44c74e5e96cc.png)

Akbil İşlemlerini seçerek devam ettik. Burada Akbil No girerek ve Akbil Tipi seçimi yaparak kayıt gerçekleştirdik.3 tip akbil seçeebiliyoruz Anne,Öğrenci ve Standart.
Aşağıda daha önceden adımıza kaydedilmiş akbilleri görebiliriz.Yukarıda bulunan anasayfa butonu ile İşlemler sayfasına dönüyoruz.
![image](https://user-images.githubusercontent.com/73429501/220540173-a0a1da36-e05a-4f94-ad1b-afbbc81e43d6.png)

Talimat İşlemleri sayfasına giderek az önce kaydetiğimiz Akbil no seçerek ve ne kadar para yükleyeceksek miktarı girerek yükleye basıyoruz. Bekleyen talimatlar aşağıda gözüküyor.Talimatın üzerine sağ tık yaparak talimatı onaylıyoruz.Sağ üstte bekelyen taliat sayısı yazmaktadır.Yukarıda yazan işlemler butonunun üzerine geldiğimizde kaydedilen talimatları XML ve Json formatında dışarı akatarabiliyoruz.Aynı zamanda içeri aktarımda yapabiliriz
![image](https://user-images.githubusercontent.com/73429501/220545044-cad8b241-be18-43b3-b88c-47a7c85862a3.png)

İşlem seçeneklerinin bulunduğu sayfadan anasayfa butonuna basarak ayarlara gidiyoruz.Bu sayfadan kullanıcı bilgilerinde güncelleme yapıyoruz.

![image](https://user-images.githubusercontent.com/73429501/220546588-9fc58e99-bf37-4ed5-98fd-874632f39fd0.png)

Aşağıda yazılan kodların bir kısmını görebilirsiniz.
![image](https://user-images.githubusercontent.com/73429501/220549761-93d1d4c8-7402-4d65-b72f-9827ce521e27.png)

![image](https://user-images.githubusercontent.com/73429501/220549916-6ed2afe4-c0ab-4d2d-8157-c6f0c9bc1f2a.png)

![image](https://user-images.githubusercontent.com/73429501/220550071-800fec4d-7036-4b73-84c7-22ad3cd44711.png)




