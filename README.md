# 📚 Akademik İşbirliği Ağı Analizi 

Bu proje, akademik makale veri setleri üzerinde **İşbirliği Ağı (Co-authorship Network)** analizi yapan, verileri işleyen ve sonuçları etkileşimli bir Web Arayüzü (GUI) ile görselleştiren bir Python uygulamasıdır.

Proje; **Graph Theory (Çizge Kuramı)**, **Binary Search Tree (BST)** ve **Shortest/Longest Path** algoritmalarını kullanarak yazarlar arasındaki ilişkileri analiz eder.

![Dil](https://img.shields.io/badge/Dil-Python-blue)
![Framework](https://img.shields.io/badge/Arayüz-Dash%20%7C%20Plotly-green)
![Analiz](https://img.shields.io/badge/Analiz-NetworkX-orange)

## 🚀 Proje Özellikleri ve İsterler

Uygulama arayüzünde bulunan butonlar, aşağıdaki algoritmik işlemleri gerçekleştirir:

1.  **İki Yazar Arasındaki En Kısa Yol (İster 1):** Girilen iki yazar ID'si (ORCID) arasındaki en kısa işbirliği yolunu bulur ve görselleştirir.
2.  **İşbirlikçilerin Sıralanması (İster 2):** Bir yazarın işbirlikçilerini, toplam makale sayılarına göre (Bubble Sort kullanılarak) sıralar ve kuyruk yapısı mantığıyla listeler.
3.  **BST Görselleştirme (İster 3):** Seçilen bir yazarın işbirlikçilerinden (belirtilen bir yazar hariç tutularak) bir **Binary Search Tree (İkili Arama Ağacı)** oluşturur ve ağaç yapısını çizdirir.
4.  **Ağırlıklı En Kısa Yollar (İster 4):** Yazarlar arasındaki ortak makale sayılarını "ağırlık" olarak kabul eder ve düğümler arası ağırlıklı yolları hesaplar.
5.  **İşbirlikçi Sayısı Analizi (İster 5):** Girilen yazarın toplam kaç farklı yazarla işbirliği yaptığını hesaplar.
6.  **En Çok İşbirliği Yapan Yazar (İster 6):** Ağdaki en yüksek dereceye (degree centrality) sahip düğümü, yani en çok kişiyle çalışan yazarı bulur.
7.  **En Uzun Yol Analizi (İster 7):** Derinlik Öncelikli Arama (DFS) ve özyinelemeli (recursive) algoritmalar kullanarak, bir yazardan başlayıp ağın uçlarına giden en uzun yolu tespit eder.

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

* **Python 3.x:** Ana programlama dili.
* **Dash & Plotly:** Etkileşimli web arayüzü ve ağ/grafik çizimleri için.
* **NetworkX:** Graf (Graph) veri yapısını oluşturmak ve temel ağ algoritmaları için.
* **Pandas:** Excel veri setini okumak ve işlemek için.
* **OpenPyXL:** `.xlsx` dosyalarıyla çalışmak için.

## ⚙️ Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

### Adım 1: Proje Klasörünü Oluşturun
Masaüstünüzde veya istediğiniz bir yerde (Örneğin: `ProlabProje`) bir klasör oluşturun.
* `main.py` (Python kodunuz)
* `dataset.xlsx` (Excel veri dosyanız)
Bu iki dosyanın **aynı klasör içinde** yan yana olduğundan emin olun.

### Adım 2: Gerekli Kütüphaneleri Yükleyin
Bilgisayarınızda Python'un kurulu olduğundan emin olun. Ardından terminali (veya CMD'yi) açın ve şu komutu yapıştırıp enter'a basın:

```bash
pip install dash plotly networkx pandas openpyxl
