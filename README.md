# İngiltere Veri Bilimci Maaş Analizi (EDA + K-Means)

Bu proje, Kaggle'dan alınan **İngiltere Veri Bilimci Maaşları** veri setini kullanarak veri analizi ve kümeleme çalışması yapmayı amaçlamaktadır.

## Amaç
- İngiltere'deki veri bilimci maaşlarını etkileyen faktörleri anlamak
- Şirketler ve şehirler bazında maaş trendlerini incelemek
- K-Means ile maaş ve şirket puanı bazlı kümeler oluşturmak

## Veri Seti
- Kaynak: Kaggle
- Sütunlar: 
  - Company: Şirket adı
  - Company Score: Glassdoor puanı
  - Job Title: İş pozisyonu
  - Date: İlan tarihi
  - Salary: Maaş
  - Skills: Pozisyon için gerekli beceriler
  - Estimation Type: Maaş tahmini kaynağı
  - Remote: Çalışma tipi
  - City, Country: Konum bilgisi

## Kullanılan Teknolojiler
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Veri ön işleme: Eksik değerleri doldurma, Label Encoding
- Görselleştirme: Barplot, Swarmplot, Scatterplot
- Makine Öğrenmesi: K-Means Kümeleme

## Adımlar
1. Veri seti yükleme ve incelenmesi
2. Eksik değerlerin doldurulması (mod ile)
3. Kategorik verilerin sayısal formata dönüştürülmesi (LabelEncoder)
4. Şehir ve şirket bazlı maaş analizleri
5. K-Means kümeleme ile maaş ve şirket puanı kümelerinin oluşturulması
6. Kümeleme sonuçlarının görselleştirilmesi ve özetlenmesi

## Bulgu Örnekleri
- En yüksek maaş veren şehir: London
- En düşük maaş veren şehir: Manchester
- Kümeleme sonuçları:
  - Cluster 0 → düşük maaş, düşük puanlı şirketler
  - Cluster 1 → orta maaş, orta puanlı şirketler
  - Cluster 2 → yüksek maaş, yüksek puanlı şirketler

## Görseller
- Şehir Bazlı Ortalama Maaş
- En Yüksek / En Düşük Maaş Veren Şirketler
- K-Means Kümeleme Sonuçları

---

> Bu proje, veri analizi ve temel makine öğrenmesi becerilerini sergilemek amacıyla hazırlanmıştır.
