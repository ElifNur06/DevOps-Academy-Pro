# 🚀 DevOps Academy

DevOps Academy, DevOps kültürünü; terminal yönetimi, CI/CD süreçleri, ağ topolojileri ve donanım yönetimi disiplinlerini oyunlaştırma (gamification) yoluyla öğreten, simülasyon tabanlı bir Flutter uygulamasıdır.

## 🛠️ Teknik Mimari
Proje, modüler bir yapı üzerine inşa edilmiştir ve durum yönetimi (state management) için `EnhancedSimulationModel` nesnesini kullanır.

| Modül | Sorumluluk |
| :--- | :--- |
| `main.dart` | Uygulama yaşam döngüsü ve merkezi dashboard yönetimi. |
| `enhanced_simulation_model.dart` | Simülasyon motoru (Isı, güç, görevler, yıpranma). |
| `terminal_screen.dart` | Sanal dosya sistemi, CLI, Docker simülasyonu. |
| `pipeline_screen.dart` | CI/CD süreçleri, hata ayıklama (puzzle) ve paralel işleme. |
| `hardware_screen.dart` | Sunucu rack yönetimi, soğutma ve bakım. |
| `game_storage.dart` | İlerleme ve kayıt (SharedPreferences). |

## ✨ Öne Çıkan Özellikler

* **Terminal & CLI:** Bash komutları (`ls`, `cd`, `cat`, `nano`), Docker yönetimi ve Nmap ağ tarama simülasyonları.
* **Pipeline & CI/CD:** Sürükle-bırak puzzle mekaniği ile pipeline tasarımı, paralel işlem desteği ve akıllı hata logları.
* **Hardware & Data Center:** Sıcaklık takibi, fan hızı yönetimi, donanım yıpranması ve tozlanma dinamikleri.
* **Hacker & Güvenlik:** Ransomware/DDoS simülasyonları, War Room entegrasyonu ve otomatik güvenlik duvarı.
* **Oyunlaştırma:** * **Chaos Monkey:** Refleks tabanlı virüs temizleme.
    * **Jokerler:** Bütçe harcayarak zamanı dondurma veya hataları oto-fixleme.
    * **Sudden Death:** Tek haklı, süre kısıtlı zorluk modu.

## ⚙️ Teknik Gereksinimler
- **Framework:** Flutter
- **Dil:** Dart
- **Veri Kalıcılığı:** `shared_preferences`
## Görseller
<img width="401" height="714" alt="image" src="https://github.com/user-attachments/assets/ab750479-130f-4f00-aeec-7f26e4fe4477" />
<img width="403" height="713" alt="image" src="https://github.com/user-attachments/assets/09aadb19-d074-4720-9b3b-d35ec76a1d70" />
<img width="402" height="716" alt="image" src="https://github.com/user-attachments/assets/b0b98586-f9b7-4c90-a5fb-5ed87614c65c" />
<img width="404" height="717" alt="image" src="https://github.com/user-attachments/assets/becd256e-5daf-4128-a97f-f4f9e102bafa" />
<img width="404" height="715" alt="image" src="https://github.com/user-attachments/assets/f903c8a9-c64d-4b03-9395-6c8f688433fc" />
<img width="402" height="716" alt="image" src="https://github.com/user-attachments/assets/08f11567-ee3f-4f71-b5b2-e98a2b4d7bfe" />
<img width="403" height="716" alt="image" src="https://github.com/user-attachments/assets/b80c589b-3c07-4def-b646-1fb3d4248bf6" />
<img width="403" height="717" alt="image" src="https://github.com/user-attachments/assets/80e07c4b-3094-4b7f-9cf3-0937a18866c1" />
<img width="401" height="713" alt="image" src="https://github.com/user-attachments/assets/1bb22856-e106-4254-b324-b0a4111dfac6" />
<img width="401" height="719" alt="image" src="https://github.com/user-attachments/assets/fd146274-2436-4e1e-93a7-9797ebde76af" />
<img width="400" height="716" alt="image" src="https://github.com/user-attachments/assets/6d64cf9b-9687-46f6-90f7-4b1a87cc7bc1" />
<img width="404" height="716" alt="image" src="https://github.com/user-attachments/assets/ff2e16b7-b49a-4bd3-9998-e31067c229c0" />
<img width="401" height="716" alt="image" src="https://github.com/user-attachments/assets/81db1d6e-f134-4799-9768-2105d4055ee7" />

## 🚀 Gelecek Yol Haritası
- [ ] **Multiplayer:** WebSocket entegrasyonu ile gerçek zamanlı klan savaşları (Raid).
- [ ] **Dinamik Senaryolar:** JSON tabanlı, dışarıdan güncellenebilir oyun senaryoları.
- [ ] **Skor Tabloları:** Global ve yerel kullanıcı sıralamaları.

## 👤 Geliştirici
**Elif Nur Ayhan** | 2026

---
*Bu proje, yazılım süreçlerini oyunlaştırarak öğretmeyi hedefleyen kapsamlı bir eğitim simülasyonudur.*
