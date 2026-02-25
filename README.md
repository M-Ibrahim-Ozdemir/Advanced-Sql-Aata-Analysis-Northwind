# 📊 Northwind Database: Advanced SQL Data Analysis & Business Insights

## 📌 Proje Özeti
Bu proje, köklü **Northwind** veri tabanı üzerinde gerçekleştirilmiş kapsamlı bir veri analitiği ve iş stratejisi (Business Intelligence) çalışmasıdır. Temel amaç; sadece SQL sorguları yazmak değil, ham veriyi işleyerek şirket yönetiminin (C-Level) karar alma süreçlerini destekleyecek **aksiyona dönüştürülebilir iş içgörüleri (actionable insights)** üretmektir. 

Müşteri sadakatinden (CRM) tedarik zinciri risklerine, iş gücü optimizasyonundan satış tahminlemelerine (forecasting) kadar şirketin tüm departmanlarına dokunan 9 farklı vaka (case study) incelenmiştir.

## 🛠️ Kullanılan Teknolojiler ve Analitik Yetkinlikler
* **Veritabanı:** Microsoft SQL Server (SSMS) / T-SQL
* **Gelişmiş SQL Yapıları:** Common Table Expressions (CTEs), Subqueries (Alt Sorgular), Data Aggregation (`SUM`, `COUNT DISTINCT`), Date/Time Functions (`DATEADD`, `DATENAME`), Conditional Logic (`CASE WHEN` - Pivot Tables).
* **İş Odakları:** * B2B Müşteri Analitiği & Çapraz Satış (Cross-Selling)
  * Satış Performans Ölçümü & YTD Trend Analizi
  * Tedarik Zinciri ve Kırılma Riski Yönetimi
  * Operasyonel İş Gücü Optimizasyonu

---

## 🔍 Çözülen Temel İş Problemleri ve Stratejik Çıkarımlar

### 1. Müşteri Analitiği (CRM) ve Sadakat Programı
* **VIP Müşteri Tespiti:** Veriler, şirketin gelirlerinin büyük kısmının Pareto Prensibi'ne (80/20 kuralı) uygun olarak az sayıdaki "Balina (Whale)" müşteriden (örn: Ernst Handel) geldiğini gösterdi. Bu müşteriler için "Özel Müşteri Yönetimi (KAM)" stratejisi önerildi.
* **Ürün Çeşitliliği ve Cross-Sell:** En çok farklı ürün gamını tercih eden müşterilerin favori kategorisinin "Beverages (İçecekler)" olduğu tespit edilerek, bu kitleye "Confections" gibi tamamlayıcı ürünler için A/B test kampanyaları kurgulandı.

### 2. Satış Performansı ve Çalışan Verimliliği
* **Tahminleme (Forecasting) Anomalisi:** 1997 ve 1998 yılları karşılaştırılarak büyüme oranları hesaplandı. CTE kullanılarak yapılan bu analizde, 1998 verilerinin Mayıs ayında kesilmesinden kaynaklı "Veri Anomalisi" tespit edildi ve YTD (Yılbaşından Bugüne) bazlı yeni bir tahmin modeli önerildi.
* **Hacim vs. Verimlilik:** En çok ciro yapan çalışan ile "Ortalama Sipariş Tutarı" en yüksek olan çalışanın farklı olduğu kanıtlandı. Şirket içi yetenek transferi (cross-training) stratejisi geliştirildi.

### 3. Tedarik Zinciri ve Operasyonel Optimizasyon
* **Kritik Stok Alarmı:** Dinamik zaman fonksiyonları kullanılarak son 3 ayda aktif satılan ancak stok seviyesi "Reorder Level" sınırının altına inen (hatta sıfırlanan) "Yıldız Ürünler" tespit edildi. Acil hızlandırılmış nakliye ve dinamik stok parametreleri önerildi.
* **İş Gücü Planlaması:** Gün bazlı sipariş yoğunluğu analiz edildiğinde, siparişlerin hafta içine homojen dağıldığı görüldü. Dinamik vardiya yerine "Sabit Kadro Stratejisi" ve Pazartesi sendromuna karşı çapraz eğitim (cross-training) modeli tasarlandı.

### 4. Coğrafi Pazar ve Fiyatlandırma Stratejisi
* **Premium Pazar Tespiti:** ABD pazarının hem hacim hem de "Dünya ortalamasının %34 üzerindeki" sepet tutarıyla en karlı bölge olduğu kanıtlandı. Bu pazarda fiyat kırma yerine kalite ve lojistik hızına yatırım yapılması gerektiği vurgulandı.

---

## 📂 Dosya Yapısı
* `M2M_Analytics_Case_Study.sql`: Projedeki tüm soruların uçtan uca SQL kodlarını ve yöneticiler için yazılmış detaylı "Business Insight" (İş Çıkarımı) yorum bloklarını içerir.

## 🚀 Nasıl Çalıştırılır?
1. Repoyu bilgisayarınıza klonlayın.
2. `M2M_Analytics_Case_Study.sql` dosyasını SSMS (SQL Server Management Studio) veya tercih ettiğiniz bir IDE üzerinde açın.
3. Arka planda **Northwind** veri tabanının kurulu olduğundan emin olun.
4. Sorguları çalıştırarak sonuçları ve ilgili iş yorumlarını inceleyebilirsiniz.

---
*Veriden hikaye çıkarmak ve strateji üretmek üzerine daha fazla konuşmak isterseniz, benimle iletişime geçebilirsiniz!*
