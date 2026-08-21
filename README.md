## Hi there 👋

<!--
**Zlmknc/Zlmknc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<h1 align="center">Özlem Akıncı</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/ozlem-akinci" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:zlmakinci73@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

### 🔭 Şu An Üzerinde Çalıştığım


---

### 📈 Sonuçlar

CV'de teknoloji isimleri var; burada onların **çıktıları** var:

| Proje | Yöntem Seçimi Neden Bu? | Ölçülebilir Sonuç |
|---|---|---|
| CKD Evreleme | SMOTE, hasta güvenliğini etkileyen yanlış-negatifi minimize etmek için tercih edildi (basit undersampling veri kaybettiriyordu) | Cross-validated pipeline ile leakage-free skor, SHAP ile klinik olarak anlamlı özellik önem sıralaması |
| Cell Cycle Gene Detection | Tek bir resampling yöntemi yetmedi → SMOTETomek (sentetik üretim + temizlik) hibrit olarak seçildi | 13 algoritma karşılaştırıldı, Soft-Voting Ensemble en yüksek Macro F1 & MCC'yi verdi |
| Forest Thinning (YOLOv11) | Hazır veri seti yoktu → sıfırdan video toplayıp etiketledim | Ground-truth'a karşı benchmark edilen tespit doğruluğu |

*(Repo linkleri aşağıda — commit geçmişi ve notebook'lar üzerinden süreç izlenebilir.)*

---

### 🧩 Nasıl Çalışırım

- **Leakage'a karşı paranoyakım**: Her ML projemde cross-validation pipeline'ı içine resampling/scaling'i gömerim, dışarıda bırakmam
- **Yöntemi veriye göre seçerim, tersine değil**: %14.4 sınıf dengesizliğinde tek SMOTE yetmeyince SMOTETomek'e geçtim — bu bir tercih değil, ilk denemenin yetersiz kalmasının sonucuydu
- **Veri yoksa üretirim**: Forest thinning projesinde hazır veri seti olmadığı için video verisini kendim topladım ve etiketledim

---

### 📌 Repolar

**[ckd-staging-ml](#)** — Uçtan uca CKD evreleme pipeline'ı · notebook + sonuç grafikleri
**[cell-cycle-gene-detection](#)** — 13 algoritma karşılaştırması, ensemble modeli
**[forest-thinning-yolov11](#)** — Tez projesi, veri toplama sürecinden model eğitimine
**[iot-access-control](#)** — Raspberry Pi + RFID + Odoo ERP entegrasyonu

---

### 📊 Aktivite

<div align="center">
  <!-- GitHub Genel İstatistikler -->
  <img src="https://github-readme-stats.vercel.app/api?username=Zlmknc&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  
  <!-- En Çok Kullanılan Diller -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zlmknc&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Langs" />
</div>
<!-- Kompüter başında çalışan pixel kedi animasyonu -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Trilokia/Trilokia/blog-data/rachit_bhangale_github_stats_theme.gif" width="300"/>
</p>

<!-- Aktiflik / Streak Kartı İsterseniz -->
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Zlmknc&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" />
</div>

<div align="center">
  <a href="https://github.com/Zlmknc">
    <!-- Hazırlanan özel kedi istatistik kartı -->
    <img src="./stats-cat.svg" alt="GitHub Stats" width="480" />
  </a>
</div>

📫 zlmakinci73@gmail.com · [LinkedIn](https://www.linkedin.com/in/ozlem-akinci) · Bursa, Türkiye
