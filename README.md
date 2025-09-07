# unique_names

Basit bir Python betiği: verilen isim listesindeki **benzersiz (unique)** isimlerin **sayısını** ekrana yazdırır.  
Bu proje `set` ve `len()` pratikleri içindir.

## Gereksinimler
- Python 3.8+ (öneri: 3.12+)
- Terminal / PowerShell

## Çalıştırma
Depo kökünde:
```bash
python unique_names.py
Örnek Kod
python
Kodu kopyala
names = ["Ayşe","Ali","Ali","Mehmet","Zeynep","Ayşe"]

unique_names = set(names)
unique_names_count = len(unique_names)

print(f"Mevcut isim listesi şu şekilde; {names}")
print(f"Mevcut isim listesindeki farklı isim sayısı: {unique_names_count}")
Örnek Çıktı
text
Kodu kopyala
Mevcut isim listesi şu şekilde; ['Ayşe', 'Ali', 'Ali', 'Mehmet', 'Zeynep', 'Ayşe']
Mevcut isim listesindeki farklı isim sayısı: 4
Dosya Yapısı (öneri)
Kodu kopyala
unique_names/
  unique_names.py
  README.md
Git Hızlı Komutları
bash
Kodu kopyala
git add README.md
git commit -m "Add README for unique_names (count-only version)"
git push
