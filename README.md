# Yapay Zeka Destekli İK Geri Bildirim Analiz Sistemi 🚀

Bu proje, şirket çalışanlarının geri bildirimlerini otomatik olarak analiz eden ve İK departmanlarına aksiyon planları sunan uçtan uca bir otomasyon sistemidir.

## 🛠️ Kullanılan Teknolojiler
- **n8n:** Workflow ve veri akışı yönetimi
- **Google Sheets API:** Veri tabanı ve giriş/çıkış yönetimi
- **Google Gemini API:** Doğal Dil İşleme (NLP) ile duygu analizi ve özetleme

## 🔄 Sistem Nasıl Çalışır?
1. **Google Sheets** üzerindeki çalışan geri bildirimleri n8n tarafından okunur.
2. **Gemini yapay zeka modeli**, geri bildirimi bir İK uzmanı gibi analiz ederek motivasyon durumunu ve yapılması gerekeni maksimum 1 cümleyle özetler.
3. Üretilen analiz sonucu, ilgili çalışanın satırına otomatik olarak geri yazılır.
