# 🎨 PaintPoint  
**Tür:** FPS – Area Control / Arena Shooter  
**Geliştirme Süreci:** 6 Hafta – 3 Sprint  
**Program:** Yapay Zeka ve Teknoloji Akademisi 2025 Mezuniyet Bootcamp – Grup 19  
**Platform:** PC
**Unity Version:** 6000.1.9f1

---

## 🧩 Oyun Hakkında  
**PaintPoint**, oyuncunun bir dakika boyunca hayatta kalarak belirli bir alanı kendi rengine boyamaya çalıştığı hızlı tempolu bir FPS oyunudur.  
Oyuncu, harita boyunca farklı silahlar ve güçlendirmeler toplayabilir, düşmanlarla mücadele ederken platformun olabildiğince büyük bir kısmını kendi rengine boyamaya çalışır.

- 3 farklı zorluk seviyesi  
- Birinci şahıs kamera açısı  
- Farklı silahlar, power-uplar ve dinamik haritalar  
- Web için geliştirilmiş hızlı ve akıcı bir FPS deneyimi  

---

## 🔍 Oyun Mekanikleri  
- 🟦 **Boyama Sistemi:** Mermiler yüzeyleri boyar; yüzey boyama yüzdesi oyunun kazanma/kaybetme koşulunu belirler.  
- 🔫 **FPS Savaş Sistemi:** Farklı silah tipleri, mermi yayılımı, hasar mekaniği.  
- ⚡ **Power-Up Sistemi:** Hız, hasar ve dayanıklılık gibi geçici güçlendirmeler.  
- 🗺 **Farklı Zorluk Seviyeleri:** AI davranışları ve düşman yoğunluğu zorluklara göre değişir.

---

## 👤 **Projedeki Benim Katkılarım (Online Sistemin Tamamı)**  
Son sprintte proje pivot ettiği için **multiplayer modu oyundan çıkarıldı**; ancak aşağıdaki sistemlerin tamamı tarafımca geliştirilmiş ve çalışır hâle getirilmişti.  
Bu sistemler, FPS oyunun multiplayer versiyonunun temelini oluşturuyordu.

### ✅ **1. Lobby/Menü Sunucu Sistemi**
Unity Netcode + Relay + Lobby altyapısını kullanarak:  
- Oyuncuların farklı **odalar oluşturmasını**  
- Odaya **girmesini/çıkmasını**  
- Oda bilgilerinin gerçek zamanlı güncellenmesini  
sağlayan tam işlevsel bir lobby sistemi geliştirdim.

### ✅ **2. Takım Seçimi Sistemi**
- Oyuncuların odada kendi renk takımını seçebildiği  
- Takım seçiminin lobby içinde eş zamanlı güncellendiği  
- Sunucu tarafından doğrulanan bir sistem yazdım.

### ✅ **3. Karakter Özelleştirme (Customization) Sistemi**
- Oyuncuların odadayken karakter görünüşünü değiştirebildiği  
- Seçilen görsel öğelerin tüm oyunculara **senkronize** edildiği  
- Sunucu otoritesiyle çalışan görünüş verisi aktarım sistemi geliştirdim.

### ✅ **4. Oda İçi Chat Sistemi**
- Lobby içinde çalışan gerçek zamanlı metin tabanlı chat sistemi geliştirdim.  
- Mesajların tüm oyunculara güvenli ve hızlı şekilde iletilmesi sağlandı.

> ❗ Bu dört sistem, proje pivot ettiği için final sürümden çıkarılmıştır.

---

## 🎮 Takım  
**Takım İsmi:** PentaPoint  

- İrem Büşra Sürüm — Product Owner  
- Işık Eren Çelik — Scrum Master  
- Ümmü Habibe Yüce  
- Mehmet Emir Turan  
- Abdulkadir Güç — *Multiplayer & Lobby Systems Developer*

---

## 🎥 Oynanış Videosu  
https://www.youtube.com/watch?v=X2LoJgp3D8s

---

## Projede Kullanılan Assetler ve Kaynaklar:
-https://github.com/mixandjam/Splatoon-Ink
-https://learn.unity.com/project/fps-template

--