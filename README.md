# Match Analysis - 2018 Dünya Kupası Finali

Bu projede 2018 FIFA Dünya Kupası finalini (Fransa - Hırvatistan) StatsBomb verisiyle analiz etmeye çalıştım.
Lisans seviyesinde, üniversite öğrencisi bakışıyla hazırlanmış bir notebook çalışması.

Temel fikir şu: maçı sadece skor üzerinden değil, saha içindeki aksiyon dağılımı üzerinden de okumak.

## Projede Neler Var?

- Oyuncu dokunuş yoğunluğu (heatmap)
- Takım bazlı pas yoğunluğu haritası
- Takım bazlı şut haritası (gol ve gol olmayan şutlar ayrı)
- Pas ağı (pass network)

Notebook içinde örnek olarak şu oyuncu ve takımlar için görselleştirmeler üretiliyor:

- Paul Pogba (France)
- Luka Modrić (Croatia)
- France takım analizi
- Croatia takım analizi

## Kullanılan Kütüphaneler

- numpy
- pandas
- matplotlib
- scipy
- statsbombpy
- mplsoccer

## Kurulum

1. Python 3.10+ önerilir.
2. Gerekli paketleri kur:

```bash
pip install numpy pandas matplotlib scipy statsbombpy mplsoccer
```

## Nasıl Çalıştırılır? 

1. Match_Analysis.ipynb dosyasını aç.
2. Hücreleri üstten alta doğru sırayla çalıştır.
3. Veriler çevrim içi çekildiği için internet bağlantısının açık olduğundan emin ol.

## Veri Kaynağı

Bu proje, statsbombpy kütüphanesi üzerinden gelen StatsBomb açık veri setini kullanır.

## Not

Bu çalışma, lisans düzeyinde bir maç analizi denemesi olarak hazırlandı.
Amaç ileri seviye model kurmaktan çok, oyunun ritmini ve aksiyon bölgelerini görselleştirerek anlaşılır hale getirmek.

## Lisans

Bu repo MIT Lisansı ile paylaşılmıştır. 
