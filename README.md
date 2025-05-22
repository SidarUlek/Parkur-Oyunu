# Bitirme Projesi
- 21430070041-Sidar Ülek
- 21703912-Rauf Nuriyev

# Dosya Drive Linki: 
https://drive.google.com/file/d/1aKltUhfr-m7WWU4NGcMEncMyQZC0E52x/view?usp=sharing


# 🕹️ PROJE RAPORU: FİZİK TABANLI PARKUR OYUNU
1. Proje Adı:
Fizik Tabanlı Parkur Oyunu

2. Geliştirme Ortamı
- Oyun Motoru: Unreal Engine 5
- Programlama Dili: Blueprints & C++
- Hedef Platform: PC

3. Proje Amacı
Bu projenin amacı, oyunculara hem eğlenceli hem de öğretici bir deneyim sunan, fizik kurallarına dayalı bir parkur oyunu geliştirmektir. Oyuncu, çeşitli fiziksel engelleri ve mekanikleri aşarak oyunu tamamlamaya çalışır. Proje kapsamında fizik ilkeleri (ivme, sürtünme vb.) oyun mekaniğine entegre edilmiştir.

4. Oynanış Mekanikleri
   
   ![WhatsApp-Video-2025-05-22-at-16 33 32](https://github.com/user-attachments/assets/24a6474b-d310-42bd-a2d8-a79b1bc105d5)
   
4.1 Hareket ve Parkur Dinamikleri
Oyuncu karakteri, parkur boyunca engelleri akıcı şekilde aşabilmektedir.

  ![WhatsApp-Video-2025-05-22-at-16 33 32-_1_](https://github.com/user-attachments/assets/3fcb3975-5d2c-449d-890f-47874c4f92ee)

Zıplama, atlama ve tırmanma gibi temel parkur hareketleri özel animasyonlar ve düzgün geçişlerle entegre edilmiştir.
  
  ![WhatsApp-Video-2025-05-22-at-16 33 23](https://github.com/user-attachments/assets/a45b059a-ba6a-4c8b-bcc2-ec673c637788)
  
4.2 Fizik Tabanlı Bölümler
İvme Bölgesi: Oyuncu karakteri bu alana girdiğinde, belirli fiziksel kurallara uygun şekilde zamanla yavaşlamaktadır.

  ![WhatsApp-Video-2025-05-22-at-17 46 51](https://github.com/user-attachments/assets/1f60c8d5-19b2-4fcb-ba3c-f863df1d769c)

Sürtünme Bölgesi: Zeminle karakter arasındaki sürtünme katsayısına göre hareket hızı azalmaktadır. Bu bölümde farklı zemin türleri (metal, halı, buz gibi) ile sürtünme etkisi gözlemlenebilir.

  ![WhatsApp-Video-2025-05-22-at-17 46 53](https://github.com/user-attachments/assets/0f583392-5afa-4c6e-ab2c-2fd098a1a33c)

  
Asansör Mekaniği: Oyuncunun belirli ağırlıkları taşıyıp asansöre yerleştirmesi gerekir. Doğru kütle sağlandığında asansör yukarıya çıkar. Bu sistem ağırlık dengesi prensibiyle çalışır ve gerçek dünya fiziğine uygundur.
  ![WhatsApp-Video-2025-05-22-at-16 33 26](https://github.com/user-attachments/assets/f20c0387-7b96-4783-bb9d-dd8cbf45787b)

4.3 Silah ve Ateş Etme Mekanikleri
Oyunda silah sistemi entegre edilmiştir.

  ![WhatsApp-Video-2025-05-22-at-16 33 33](https://github.com/user-attachments/assets/655267be-b2ee-4cf4-b85f-aa743825166a)

Silah mekaniği hem animasyon hem de ses efektleriyle desteklenmiştir.

5. Teknik Özellikler
- Karakter Kontrolleri: Gelişmiş kamera ve kontrol sistemi ile akıcı bir kullanıcı deneyimi sağlanmaktadır.
![Silah konum Işınlama ve reload](https://github.com/user-attachments/assets/3e56cfc3-99a2-475e-bc7c-0f32b155ce46)
![Silah anımasyon geçişleri](https://github.com/user-attachments/assets/65725ca0-d447-4491-8f49-982af2db2d37)
![Mermi ses ve spawn](https://github.com/user-attachments/assets/9bbcf02d-f25a-4e2c-ba0a-ecf88a7ab698)
![Mermi doğrultusu ve menzili](https://github.com/user-attachments/assets/6fb0361c-86c7-42b5-b4c9-b914a4cffc7d)
![SilahAnimasyonlarıve ses efekleri](https://github.com/user-attachments/assets/23623677-0679-4ca0-8151-b80511b8cfd4)
![Silah tutma animasyonu](https://github.com/user-attachments/assets/a92b49a7-6c02-4254-a679-448ff0de1029)


- Animasyon Sistemi: Parkur hareketleri (tırmanma, zıplama, atlama) özel animasyon blueprintleri ile senkronize edilmiştir.
![karakter blueprinti](https://github.com/user-attachments/assets/f7fefe55-5cf0-416b-a840-7c4682444213)
![Karakter eğim](https://github.com/user-attachments/assets/128743a3-d6a4-49ca-a341-965bdd14908b)
![Karakter eğim2](https://github.com/user-attachments/assets/0b4d2ddc-579c-43ae-9a79-5451eb41ed95)

- Fizik Sistemi: Unreal Engine 5’in fizik motoru kullanılarak sürtünme, ivme ve ağırlık değişimleri gerçeğe uygun biçimde hesaplanmaktadır.

![Sürtünme kuvveti](https://github.com/user-attachments/assets/ddbe3ba8-fb27-47ce-b30b-919fba5f872d)
![ivme durması](https://github.com/user-attachments/assets/29d49836-5ce2-4bd9-ae11-6b6550bb4ca9)
![İvme blueprint](https://github.com/user-attachments/assets/0e26fe6b-83e6-48e0-a515-fb468e4fd632)
![PortalBlueprint](https://github.com/user-attachments/assets/0357d9d7-42c8-4d39-b3d3-123fdd8dfc4a)
![PortalAnimasyon](https://github.com/user-attachments/assets/db1ff5f0-d75f-4d41-80c0-9717c561f259)
![asansör](https://github.com/user-attachments/assets/15c45429-9fd7-4f4d-853f-8598a131640f)
![100NKutu](https://github.com/user-attachments/assets/c792559a-7448-4917-b729-f901321cf366)

- UI/UX: Oyuncunun ağırlık değerini görmesi, kalan süreyi takip etmesi gibi arayüz unsurları projeye eklenmiştir.

![zamanlayıcı başlangıç](https://github.com/user-attachments/assets/ed648411-55be-478e-a1d1-3806494812ff)
![Widgetleri ekrana ekleme](https://github.com/user-attachments/assets/efa7d78c-5d72-4367-aca6-69c710880c2e)
![TimerDurdurucu](https://github.com/user-attachments/assets/a9a37591-1543-4f63-add3-42614c1d9353)

- Harita Tasarımı: Oyun, bölümler hâlinde yapılandırılmış açık ve yarı kapalı alanlardan oluşmaktadır. Her bölüm, fizik tabanlı oyun mekaniklerini test etmeye yönelik olarak tasarlanmıştır.

![Map1](https://github.com/user-attachments/assets/5452b1cf-f63c-4b7f-a0ce-95f020288cca)
![Map2](https://github.com/user-attachments/assets/4739d554-46fc-415b-8857-e9540bc8da16)
![map3](https://github.com/user-attachments/assets/be12d708-8a87-4e72-b3f7-0cab06cfdb34)
![map4](https://github.com/user-attachments/assets/98e5d3bf-7814-4205-b42d-e058956c558e)

6. Öğrenme Hedefleri / Katkıları
Bu proje ile fizik kurallarının oyun ortamına nasıl entegre edilebileceği öğrenilmiştir. Özellikle:

- Gerçek dünya fiziği ile oyun mekaniği arasında köprü kurma,

- Blueprint sistemleriyle etkileşimli objeler oluşturma,

- Oyuncu deneyimini artıran fizik tabanlı tasarım yöntemleri geliştirme becerileri kazanılmıştır.

7. Sonuç ve Değerlendirme
- Bu proje, Unreal Engine 5 kullanılarak geliştirilen fizik temelli bir parkur oyununun temel oyun mekaniği, fiziksel hesaplamalar ve kullanıcı etkileşimi açısından örnek bir uygulamasıdır. Oyunun hem eğlenceli hem de öğretici yapısı, oyun geliştiriciler ve öğrenciler için ilham kaynağı olabilir.

