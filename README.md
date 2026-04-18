# 🏠 Daşınmaz Əmlak Satışı və m² Qiyməti Hesabatı (Power BI)

![Power BI](https://img.shields.io/badge/Visualization-Power%20BI-yellow?style=flat-square&logo=power-bi)
![Python](https://img.shields.io/badge/Data%20Cleaning-Python-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=flat-square&logo=pandas)
![Kaggle](https://img.shields.io/badge/Source-Kaggle-20BEFF?style=flat-square&logo=kaggle)

## 📌 Layihənin İcmalı
Bu layihə, Kaggle-dan əldə edilmiş məlumat dəsti əsasında qurulmuş **ucdan-uca (end-to-end) daşınmaz əmlak analitikası** iş axınıdır. Layihənin məqsədi xam mənzil satış məlumatlarını təmiz və analizə hazır vəziyyətə gətirmək, satış performansı və m² üzrə orta qiymətə fokuslanan interaktiv **Power BI dashboard** hesabatı hazırlamaqdır.

---

## 🛠 Alətlər və Texnologiyalar
* **Python (JupyterLab):** Məlumatların təmizlənməsi və ilkin emalı (Preprocessing).
* **Pandas / NumPy:** Boş dəyərlərin, dublikatların idarə edilməsi və formatlaşdırma.
* **Seaborn / Matplotlib:** Kəşfiyyatçı Məlumat Analizi (EDA) və vizuallaşdırma.
* **Power BI:** Hesabat və interaktiv panelin (dashboard) hazırlanması.
* **GitHub:** Layihənin sənədləşdirilməsi və paylaşılması.

---

## ⚙️ Məlumatların Təmizlənməsi (Python)
JupyterLab mühitində həyata keçirilən əsas təmizləmə addımları:
* Təkrarlanan (duplicate) sətirlərin silinməsi.
* Boş qalan (`null`) dəyərlərin tənzimlənməsi.
* Yanlış və ya çatışmayan dəyərlərin düzəldilməsi.
* Sütunların düzgün məlumat tiplərinə (ədədi, kateqorial və s.) çevrilməsi.
* Paylanma xüsusiyyətlərinə uyğun olaraq çatışmayan dəyərlərin **orta (mean)** və ya **median** ilə doldurulması.

---

## 📊 Kəşfiyyatçı Məlumat Analizi (EDA)
Təmizləmə prosesindən sonra **Seaborn** və **Matplotlib** kitabxanaları vasitəsilə aşağıdakı analizlər aparılmışdır:
* Qiymət paylanması və kənar meyllərin (outliers) müəyyən edilməsi.
* Otaq sayına görə m²-nin orta qiymət dəyişimi.
* Sahə növü (Area type) ilə satış payı arasındakı əlaqə.
* m² üzrə orta qiymətin ən yüksək olduğu top ərazilər.

---

## 🖥 Power BI Dashboard-un Üstünlükləri
Hazırlanmış interaktiv paneldə aşağıdakı əsas göstəricilər əks olunub:
* **Ümumi Gəlir** və **Satılan Evlərin Sayı**.
* **m² üzrə Orta Qiymət**.
* Ən baha 10 ərazinin siyahısı.
* Otaq sayına görə orta qiymət analizi.
* Sahə növünə görə satış payı.
* Otaq və hamam otağı sayına görə satışın sıxlıq matrisi (heatmap).

---

## 🔍 Əsas Analitik Nəticələr
* **Regional Fərqlər:** Müəyyən ərazilərdə m² üzrə orta qiymət digərlərinə nisbətən əhəmiyyətli dərəcədə yüksəkdir.
* **Tələb vs Qiymət:** Daha çox otağı olan mülklərdə m² qiyməti artsa da, alıcı tələbi (satış sayı) əsasən orta seqmentli evlərdə pik həddə çatır.
* **Sahə Seçimi:** Satış payı sahə növünə görə ciddi şəkildə fərqlənir, bu da alıcıların fərqli əmlak növlərinə olan meyllərini göstərir.

---
## Dashboard Preview
https://app.powerbi.com/view?r=eyJrIjoiMTlkNGEyNTgtN2Q0MC00OWZkLWE3ZDktYmUxYTA0MzA3YmZkIiwidCI6ImZkYTYyMDk1LWI3ZGQtNGNjOS05MTIwLWZkMDYzODg5Y2Q0OCIsImMiOjl9


