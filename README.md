# Proje Ödevi 1. Adım: Proje Açıklaması ve Araç Seçimi

## Proje Adı: "Risona" - Bağımsız Müzisyen Keşif Platformu

### 1. Proje Fikrinin Açıklaması

**Problem:**
Günümüzün müzik endüstrisi, büyük plak şirketleri ve popüler sanatçılar tarafından domine edilmektedir. Bu durum, kariyerinin başındaki veya ana akım dışında müzik üreten bağımsız müzisyenlerin kitlelere ulaşmasını, yeteneklerini sergilemesini ve kendi özgün seslerinin dinleyicilerde bir karşılık bulmasını (resonate) zorlaştırmaktadır. Aynı şekilde, müzikseverler de sürekli aynı isimler yerine yeni ve keşfedilmemiş tınılar bulmakta zorluk çekmektedir.

**Çözüm:**
"Risona", bu problemi çözmek amacıyla geliştirilmiş bir No-Code web platformudur. Platform, ismini aldığı "resonate" (yankılanmak, tınlamak) felsefesiyle, bağımsız müzisyenlerin seslerinin dinleyicilerde bir etki bırakmasını hedefler. Müzisyenler kendi profillerini oluşturabilir, müziklerini (SoundCloud, YouTube vb. linkler üzerinden) paylaşabilir ve etkinliklerini duyurabilirler. Dinleyiciler ise türe, şehre veya enstrümana göre filtreleme yaparak yeni sanatçılar keşfedebilir ve favori müzisyenlerini takip edebilirler.

### 2. Hedef Kitle

* **Bağımsız Müzisyenler:** Kendi müziğini üreten ve daha geniş kitlelere ulaşmak isteyen her türden sanatçı.
* **Müzikseverler ve Keşifçiler:** Yeni ve özgün müzikler dinlemekten hoşlanan, yerel sanatçılara destek olmak isteyen kitle.
* **Mekan Sahipleri ve Organizatörler:** Canlı müzik etkinlikleri için yeni yetenekler arayan işletmeler.

### 3. Temel Özellikler

* **Müzisyen Profilleri:** Biyografi, fotoğraf, sosyal medya linkleri ve müzik portfolyosu.
* **Müzik Keşif Motoru:** Tarz, enstrüman ve lokasyona göre arama ve filtreleme.
* **Etkinlik Takvimi:** Müzisyenlerin konserlerini ve canlı performanslarını listeleyebileceği bir takvim.
* **Takip Sistemi:** Kullanıcıların beğendikleri sanatçıları takip ederek güncellemelerinden haberdar olması.

### 4. No-Code / Low-Code Araç Seçimi ve Gerekçesi

**Seçilen Araç: Bubble**

**Gerekçe:**
Bu proje için **Bubble** platformunun seçilmesinin temel nedenleri şunlardır:

1.  **Esneklik ve Kapsamlı Veritabanı:** Proje, müzisyenler, kullanıcılar, şarkılar ve etkinlikler gibi birbiriyle ilişkili birden çok veri türünü yönetmeyi gerektirir. Bubble'ın yerleşik ve tamamen özelleştirilebilir veritabanı, bu karmaşık veri yapısını rahatlıkla yönetmemizi sağlar.
2.  **Gelişmiş Kullanıcı Yönetimi:** Platformda "Müzisyen" ve "Dinleyici" gibi farklı kullanıcı rolleri olacaktır. Bubble, farklı roller için özel kayıt/giriş işlemleri, profil sayfaları ve yetkilendirmeler oluşturmaya olanak tanıyan güçlü bir kullanıcı yönetim sistemine sahiptir.
3.  **Özelleştirilebilir Arayüz (UI):** Glide gibi daha şablon tabanlı araçların aksine Bubble, arayüz tasarımında "pixel-perfect" kontrol sunar. Bu sayede platformun marka kimliğine uygun, özgün ve kullanıcı dostu bir tasarım oluşturmak mümkündür.
4.  **İş Akışları (Workflows):** "Bir kullanıcı bir müzisyeni takip ettiğinde bildirim gönder" veya "Yeni bir etkinlik oluşturulduğunda ana sayfada göster" gibi karmaşık mantıksal işlemleri kod yazmadan, görsel iş akışları ile oluşturma imkanı sunar. Bu, projenin temel fonksiyonelliği için kritik öneme sahiptir.
5.  **API Entegrasyonları:** Gelecekte platforma Spotify veya SoundCloud gibi servislerden doğrudan müzik çekme özelliği eklemek istersek, Bubble'ın API Connector eklentisi bu entegrasyonları kolayca yapmamızı sağlar.

Sonuç olarak Bubble, "Risona" gibi çok kullanıcılı, veri odaklı ve özgün bir web uygulaması geliştirmek için gereken güç, esneklik ve ölçeklenebilirliği sunan en ideal No-Code aracıdır.
