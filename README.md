# Smart Survey Analyzer 📊
Python tabanlı, dinamik veri üretimi ve döngü mekanizmaları ile çalışan öğrenci memnuniyet analiz sistemi.

## 📌 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)
- [İletişim](#iletişim)

## 📖 Proje Hakkında
Bu proje, üniversite bünyesindeki öğrenci memnuniyet anketlerini dijital ortamda simüle etmek ve analiz etmek amacıyla geliştirilmiştir. Özellikle belirsiz veri setleri üzerinde **döngülerin (for/while)** ve **kontrol mekanizmalarının (break/continue/pass)** veri analizi süreçlerindeki kritik rolünü uygulamalı olarak göstermektedir.

## ✨ Özellikler
- ✔️ **Dinamik Veri Üretimi:** `random` modülü ile gerçekçi ve belirsiz anket sonuçları simülasyonu.
- ✔️ **Gelişmiş Filtreleme:** Geçersiz verilerin (örn: 6 puanı) `continue` ile otomatik ayıklanması.
- ✔️ **Erken Uyarı Sistemi:** Arka arkaya 3 adet düşük puan (1) tespit edildiğinde `break` ile sürecin durdurulması.
- ✔️ **Kategorik Analiz:** Puanların "Memnun", "Kararsız" ve "Memnun Değil" olarak sınıflandırılması.
- ✔️ **İstatistiksel Raporlama:** Ortalama, minimum ve maksimum değerlerin otomatik hesaplanması.

## 🛠 Kullanılan Teknolojiler
- **Dil:** Python 3.x
- **Kütüphaneler:** `random` (Veri simülasyonu için)
- **Metodoloji:** Temel Veri Analizi (Sum, Len, Round fonksiyonları)

## ⚙️ Kurulum

1. Repoyu klonlayın:
```bash
git clone [https://github.com/isilbilasa/smart-survey-analyzer.git](https://github.com/isilbilasa/smart-survey-analyzer.git)
```
2.Proje dizinine gidin:
```bash
cd smart-survey-analyzer
```
## 🚀 Kullanım
Uygulamayı başlatmak için terminale şu komutu yazın:
```bash
python analyzer.py
```
Not: Veri giriş aşamasında 0 tuşuna basarak süreci manuel olarak sonlandırabilir veya sistemin 3 adet düşük puan sonrası verdiği uyarıyı test edebilirsiniz.

## 📂 Proje Yapısı

```text
.
├── src/
│   └── analyzer.py       # Ana analiz algoritması ve döngü yapıları
├── docs/
│   └── report.pdf        # Projenin akademik detaylarını içeren teknik rapor
├── .gitignore            # Git tarafından takip edilmeyecek dosyalar
└── README.md             # Proje dokümantasyonu ve kullanım kılavuzu
```
## 📧 İletişim
**GitHub:** @isilbilasa
