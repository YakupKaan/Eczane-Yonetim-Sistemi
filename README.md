# 💊 Eczane Yönetim Sistemi (SQL Tabanlı)

Bu proje, bir eczanenin stok takibi, sipariş ve reçete işlemlerini kapsayan bir **ilişkisel veritabanı yapısını** içermektedir. Proje kapsamında **SQL Server (MSSQL)** kullanılarak güçlü bir veritabanı modeli oluşturulmuş, tablolar arası ilişkiler, veri bütünlüğü ve sorgu altyapısı detaylı bir şekilde yapılandırılmıştır.

---

## 🗂 Proje İçeriği

### 📌 Veritabanı: `EczaneProjesi`
Proje içerisinde aşağıdaki tablolar ve ilişkiler yer almaktadır:

- **Temel Tablolar**:  
  `Eczaneler`, `İlaclar`, `Musteriler`, `Personeller`, `Stoklar`, `İlceler`, `Tedarikci`, `Siparisler`, `SiparisDetay`, `Satıslar`, `Satıs_Detay`

- **Özellikler**:
  - Tablolar arası güçlü ilişkiler (FK)
  - Veri tutarlılığı için UNIQUE, CHECK ve PRIMARY KEY kısıtlamaları
  - Gerçekçi örnek verilerle önceden doldurulmuş
  - Gelişmiş sorgular, **Stored Procedure**, **Trigger**, **View**, **Function** örnekleri

---

## ✅ Genişletilebilirlik: Masaüstü Uygulamaya Dönüşüm

Bu SQL veritabanı yapısı, sadece birkaç kolay adımla bir **masaüstü uygulama** haline getirilebilir:

- `ADO.NET` kullanarak SQL Server’a bağlantı sağlanabilir
- `C# / .NET (WinForms veya WPF)` ile görsel bir kullanıcı arayüzü oluşturulabilir
- Arayüzde; eczane, ilaç, müşteri, satış işlemleri kolayca yönetilebilir
- Mevcut sorgular ve prosedürler doğrudan UI butonlarına bağlanabilir

🎯 **Yani bu proje, kullanıcı arayüzü katmanı eklendiğinde eksiksiz bir eczane otomasyon sistemi olarak çalışmaya hazırdır.**

---

## 🔧 Kullanım

1. `EczaneProjesi.sql` dosyasını SQL Server Management Studio (SSMS) ile açın.
2. Sorguyu çalıştırarak veritabanı ve tüm tabloları oluşturun.
3. Tüm veriler, ilişkiler ve örnek kayıtlar otomatik olarak yüklenecektir.
4. İsteğe bağlı olarak C# üzerinden uygulama geliştirilebilir.

---

## 📚 Kullanılan Teknolojiler

| Katman       | Teknoloji     |
|--------------|----------------|
| Veritabanı   | SQL Server     |
| Dil          | T-SQL          |
| Yapı         | İlişkisel Model|

---

## ✍️ Not

Bu proje yalnızca **veritabanı modellemesi ve SQL işlemleri** için hazırlanmıştır. C# arayüzü dahil edilmemiştir. Ancak hazır yapısıyla, arayüz eklemek oldukça kolaydır.

---

## 🧑‍💻 Geliştirici

Yakup Kağan BÜLBÜL 
📧 yakupkaganbulbul7@gmail.com

---

