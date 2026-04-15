# ZULAS

## Akıllı Buzdolabı & Tarif Asistanı

Ürün Gereksinim Dokümanı (PRD) • MVP Kapsamı

| Program | Future Talent Program — Modül 301: App Preneur |
| --- | --- |


| Tarih | Nisan 2026 |
| --- | --- |


| Versiyon | v1.0 - MVP |
| --- | --- |


| Gelir Modeli | Freemium + Abonelik (Subscription) |
| --- | --- |


| Hedef Platform | iOS • Android v2 |
| --- | --- |


## 1. Uygulama Fikri & Problem Tanımı

#### Problem

Her gün milyonlarca insan "Bugün ne pişirsem?" sorusunun cevabını bulamıyor. Bunun iki somut sonucu var:

  1. Karar Yorgunluğu & Mental Yük: Özellikle çalışanlar ve öğrenciler için gün sonunda yemek planlamak, "hızlı rahatlama" gerektiren ağır bir zihinsel sürece dönüşüyor.

  2. Maddi ve Manevi İsraf: Buzdolabındaki malzemelerin takip edilememesi nedeniyle yiyeceklerin çöpe gitmesi, doğrudan maddi kayıp ve israf acısı yaratıyor.

#### Fırsat (Roadmap)

Pazardaki mevcut uygulamaların iki kritik hatası bizim yol haritamızı (roadmap) oluşturuyor:

  1. Hantal Süreçler (Manuel Giriş): Rakipler malzemelerin tek tek yazılmasını bekliyor; oysa kullanıcılar "büyük çözümler" değil, anında sonuç istiyor.

  2. Kültürel Boşluk (Yerelleştirme): Mevcut tariflerin Türk mutfağına ve damak tadına uzak olması, Türkiye pazarında büyük bir boşluk yaratıyor.

Bu iki boşluk, bizim roadmap'imizdir.

#### Değer Önerisi

| Konsept | Acı (Pain) | Kazanç (Gain) |
| --- | --- | --- |
| Zulas: AI Akıllı Mutfak | Karar yorgunluğu ve israf kaynaklı para kaybı | Fotoğraf çekerek saniyeler içinde Türk mutfağından tarif alma |


## 2. Pazar Araştırması & Rakip Analizi

#### Mevcut Rakipler

| Rakip | Güçlü Yön | Zayıf Yön (Fırsat) |
| --- | --- | --- |
| Fridge AI (DuckMa) | Geniş tarif veritabanı, expiry uyarısı | Türkçe desteği yok, nesne tanıma hataları kullanıcıda "zaman kaybı" yaratıyor |
| Fridge Leftovers AI | Basit UX, ücretsiz başlangıç | Analiz sınırı düşük, Türk damak tadına hitap etmiyor |
| RecipifyAI | Kalori takibi, sesli anlatım | Arayüz karmaşıklığı ders notundaki "sadelik" ilkesine aykırı |
| Mr. Cook | Çok platform, temiz tasarım | Pahalı abonelik modelleri ve yetersiz ücretsiz deneme hakkı |


#### Rakiplerden Çıkan İçgörüler

  1. Doğruluk Sorunu: App Store yorumları analiz edildiğinde en büyük acı noktasının "Yanlış malzeme tanıma" olduğu görülmüştür. Bu, Zulas için en önemli teknik hedefi belirler.

  2. Roadmap Yakıtı: Rakiplerin sahip olmadığı "Türk Mutfağı" odağı, bizim pazara giriş biletimizdir. Kullanıcılar eldeki malzemeyle "uluslararası bir sos" değil, "hızlı bir menemen" yapmak istiyor.

  3. Sadelik Kazandırır: Rakiplerin karmaşık UI yapıları, ders notundaki "İyi ürün = çıkarılan feature sayısı" mantığıyla elenecek ve Zulas en yalın haliyle sunulacaktır.

Mini kural: "Rakiplerin hataları senin roadmap'in olabilir."

## 3. Value Proposition Canvas

| Boyut | Detay |
| --- | --- | 
| Hedef Kullanıcı | Evde yemek yapan, 20–45 yaş arası, mutfakta hız ve pratiklik arayan Türkiye'deki yetişkinler. |
| Customer Jobs | Hızlı yemek kararı vermek, zaman kazanmak, eldeki malzemeyi israf etmeden sağlıklı ve lezzetli bir öğün hazırlamak. |
| Pains (Acılar) | Gün sonu "Ne pişirsem?" stresi, malzemenin bozulmasıyla oluşan para kaybı, yabancı uygulamalardaki çeviri ve malzeme bulma derdi. |
| Gains (Kazançlar) | Saniyeler içinde hızlı rahatlama, sıfır israfın verdiği huzur, Türk damak tadına (kültürel uyum) uygun pratik öneriler. |
| Değer Önerisi | "Buzdolabını fotoğrafla, Türk mutfağından tarifini al." |

İnsanlar ürün değil, acıdan kaçış + fayda satın alır. Zulas; "ne pişirsem?" acısını azaltır ve zaman & kolaylık kazancı sunar.

## 4. MVP Kapsamı

#### Önceliklendirme Matrisi (Eisenhower)

Ders notuna göre feature'ları Eisenhower Matrisi ile sınıflandırdık:

| Özellik | Tür | Eisenhower | Gerekçe |
| --- | --- | --- | --- |
| AI Fotoğraf Analizi | Must-have | Önemli + Acil → MVP | Ürünün temel değer önerisi budur. |
| Türk Mutfağı Tarif Önerisi (3 tarif) | Must-have | Önemli + Acil → MVP | Kullanıcıya hızlı rahatlama sağlar. |
| Tarif Detay Ekranı (adımlar + malzeme) | Must-have | Önemli + Acil → MVP | Tarif işe yaramaz aksi halde. |
| Malzeme Onay Ekranı | Must-have | Önemli + Acil → MVP | Rakiplerin "yanlış tanıma" hatasını çözer. |
| Son Kullanma Tarihi Uyarısı | Nice-to-have | Önemli + Acil Değil → Backlog | Malzeme israfı pain'ini doğrudan çözer. |
| Diyet Filtresi (vejetaryen, az yağlı) | Nice-to-have | Önemli + Acil Değil → Backlog | Geniş kullanıcı kitlesine ulaşır. |
| Kalori Takibi & Diyetisyen | Nice-to-have | Önemsiz → Backlog | MVP kapsamını karmaşıklaştırır. | 
| Haftalık Yemek Planı | Nice-to-have | Önemsiz → Backlog | Version 2 hayalleri. |
| Sosyal Paylaşım | Nice-to-have | Önemsiz → Backlog | Version 2 hayalleri. |

#### MVP Akışı

Sadelik prensibi: Açılır açılmaz kamera butonu görünür olmalı.

### 📷 Fotoğraf Çek
Buzdolabını fotoğrafla

↓

### 🍽️ Malzemeleri Onayla
AI listeler, sen onaylarsın

↓

### 👨‍🍳 Tarifi Al
 3 Türk yemeği önerisi

↓

### 🔥 Pişir!
Adım adım rehber

## 5. Ürün Gereksinim Dokümanı (PRD)

#### 5.1  Problem Tanımı

  - Kullanıcı Acısı (Pain): "Bugün ne pişirsem?" sorusuyla vakit kaybetmek ve dolaptaki malzemeleri takip edemeyip israf etmek.

  - Fırsat: Rakiplerin manuel veri girişi gerektirmesi ve Türk mutfağını desteklememesi — bu boşluk bizim roadmap'imiz.

  - Değer Önerisi: Fotoğraf analizi ile saniyeler içinde Türk mutfağına özel tarif çözümü sunmak.

#### 5.2  Hedef Kullanıcı

| Segment | Profil | Temel İhtiyaç |
| --- | --- | --- |
| Çalışan Yetişkin | 25–40 yaş, haftanın 5 günü evde yemek yapar | İşten sonra hızlı karar — sıfır düşünce enerjisi |
| Üniversite Öğrencisi | 18–25 yaş, kısıtlı bütçe ve malzeme | Elimdekileri değerlendirmek |
| Ebeveyn | 30–45 yaş, aile için sağlıklı yemek | Hem sağlıklı hem hızlı tarif |


#### 5.3  Kullanıcı Hikayeleri (User Stories)

Format: "Bir [kullanıcı tipi] olarak [eylem] istiyorum çünkü [gerekçe]."

| ID | User Story |
|----|------------|
| US-1 | Bir çalışan olarak dolabımın fotoğrafını çekip ne pişirebileceğimi görmek istiyorum çünkü işten sonra yemek düşünerek vakit kaybetmek istemiyorum. |
| US-2 | Bir kullanıcı olarak sadece elimdeki malzemelerle yapılabilecek tarifler görmek istiyorum çünkü markete gitmeden yemek hazırlamak istiyorum. |
| US-3 | Bir kullanıcı olarak son kullanma tarihi yaklaşan malzemeleri öncelikli görmek istiyorum çünkü yiyeceğimi çöpe atmak istemiyorum. |
| US-4 | Bir vejetaryen kullanıcı olarak diyet filtresini seçmek istiyorum çünkü beslenme tercihlerime uygun tarifler görmek istiyorum. |


#### 5.4  MVP Özellik Listesi (Feature List)

Eisenhower Matrisi — "Önemli + Acil" kuralına göre belirlenmiştir:

| # | Özellik | Tür | Açıklama |
| --- | --- | --- | --- | 
| F-01 |AI Vision — Fotoğraf Analizi | Must-have | Fotoğraftan malzeme tanıma (Gemini Vision API) |
| F-02 | Türk Mutfağı Tarif Motoru | Must-have | Algılanan malzemelere göre 3 alternatif Türk tarifi |
| F-03 | Tarif Detay Ekranı | Must-have | Adım adım yapılış + malzeme listesi |
| F-04 | Diyet Filtresi | Nice-to-have | V2 — Vejetaryen, az yağlı, glutensiz seçenekleri |
| F-05 | Son Kullanma Tarihi Uyarısı | Nice-to-have | V2 — Bozulmak üzere olan malzemeleri öne çıkar |
| F-06 | Favorilere Ekleme | Nice-to-have | V2 — Beğenilen tarifleri kaydetme |
| F-07 | Market Listesi | Nice-to-have | V2 — Eksik malzemeleri otomatik listeye ekleme |
| F-08 | Kalori & Makro Takibi | Nice-to-have | V2 — Kişisel sağlık analizi |


#### 5.5  Teknik Gereksinimler

  - AI Modeli: Görüntü işleme ve doğal dil için Gemini Vision API entegrasyonu.

  - Tarif Veritabanı: Türk mutfağı odaklı, en az 500 tarif.

  - Platform: iOS öncelikli native uygulama; Android v2.

  - Veri Yönetimi: RevenueCat altyapısı ile Freemium + Abonelik modeli.

  - Güvenlik: Fotoğraf verileri cihazda işlenir, sunucuya gönderilmez (KVKK uyumu).

#### 5.6  Kullanıcı Deneyimi (UX) Akışı

  - Sadelik prensibi: Uygulama açılır açılmaz kamera butonu görünür olmalı.

  - Akış: Fotoğraf Çek → Malzemeleri Onayla → Diyet Filtresi Seç → Tarifi Al → Pişir!

  - Minimalizm: Her feature'a sor — "Bunu silsem uygulama hala çalışır mı?"

#### 5.7  Başarı Kriterleri — Definition of Done (DoD)

| Kriter | Hedef | Ölçüm Yöntemi |
| --- | --- | --- |
| Kod yazılmış & test edilmiş | Tüm MVP feature'ları çalışır | QA testi |
| AI tanıma doğruluğu | %85 ve üzeri | 100 farklı buzdolabı fotoğrafı testi |
| Gerçek kullanıcı testi | 100 kullanıcı ilk haftada | Beta testi katılımcıları |
| Aktif kullanım | Haftada 3+ oturum/kullanıcı | Analytics verisi |
| Doküman yayını | GitHub main branch'e push | GitHub commit kaydı |


## 6. Gelir Modeli

| Plan | Fiyat | Kapsam |
| --- | --- | --- |
| Freemium | Ücretsiz | Günde 3 fotoğraf analizi, temel tarifler |
| Premium | ₺79 / ay | Sınırsız analiz, diyet filtreleri, expiry uyarısı |
| Yıllık | ₺599 / yıl | Tüm premium özellikler + öncelikli destek |


Neden Subscription?: "Sürdürülebilir gelir = abonelik modeli."

