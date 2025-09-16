
<p align="center">
<img src="website\static\images\logo11.png" alt="logo" width="110" height="100">
<p>

<h3 align="center"> Real Time Violence Detection </h3>

<p align="center"> "İnsanı anla riskleri sıfırla"
<br>
</p>

## Real Time Violence Detection
Hastane güvenlik kameralarındaki şiddet olaylarını tespit etmek için geliştirilen bu sistem, önceden kaydedilmiş video görüntülerini makine öğrenimi ve görüntü işleme teknikleriyle analiz ederek potansiyel tehditleri belirler. Amaç, hem hastalar hem de sağlık personeli için daha güvenli bir ortam sağlamaktır.

Projede ayrıca güvenlik görevlilerinin kamera görüntülerine erişip tehditleri inceleyebileceği ve hızlı müdahale edebileceği bir web arayüzü bulunur. Bu sayede durumsal farkındalık artırılması amaçlanmıştır.

## İçindekiler
[Kullanılan Teknolojiler](#Kullanılan-Teknolojiler)

[Kurulum](#Kurulum)

[Örnek Sayfalar](#Örnek-Sayfalar)




## Kullanılan Teknolojiler 

-	Backend
    - Framework: Flask (Python)
    - Database: SQLite (database.db) 
       - Key Modules:
	__init__.py: Uygulama başlatma ve yapılandırma

          auth.py: Kullanıcı kimlik doğrulamasını ve oturum yönetimini gerçekleştirir.

          models.py: Veritabanı şemalarını tanımlar.

          routes.py and
          views.py: Yönlendirme ve iş mantığını yönetme.

-	Frontend

    - Techonologies: HTML, CSS, JavaScript

    - Templates:
    about.html: Hakkında sayfası

    - login.html: Giriş sayfası 

    - home.html:  Ana Sayfa 

    - Panel.html: Güvenlik Şefi paneli

        Static Files:
     - CSS: custom.min.css, screen.min.css JavaScript: index.js

     -  Görseller ve Videolar: UI geliştirmeleri için çeşitli multimedya varlıkları içerir.



## Kurulum
- Depoyu klonla : 
```bash
'git clone https://github.com/Cilensutas19/Real-Time-Violence-Detection.git'
```

```bash
pip install flask
pip install flask-sqlalchemy
pip install flask-login
pip install Flask-Mail
pip install Flask-Migrate
```
## Örnek Sayfalar

<p align="center">
<img src="website\static\images\ilk sayfa.jpg" alt="logo" width="400" height="240">
<p>

<p align="center">
<img src="website\static\images\ana_sayfa.jpg" alt="logo" width="400" height="240">
<p>

                                                                                      

