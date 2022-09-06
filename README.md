# Data Manipulation work with pandas

Bu repo yeni başlayanlara özel [Pandas](https://pandas.pydata.org/) kütüphanesi ile Veri Manipülasyonu için hazırlamış olduğum bir kaynak niteliğindedir. İçerisinde bir adet README dosyası, bir adet de data-manipulation-work-with-pandas.ipynb barındırıyor.

![image](https://assets.datacamp.com/production/course_22066/shields/original/shield_image_course_22066_20220125-1-1j2lvkm?1643107261)
---

---
## Öğreneceğimiz Alt Başlıklar
1. Transforming DataFrames
2. Aggregating DataFrames
3. Slicing and Indexing DataFrames
4. Creating and Visualizing DataFrames
---
## Veri Setlerini Tanıyalım
- avocado: Yıllara göre satılan avokado sayılarını içeren bir veri setidir.
- homelessness: Her ABD eyaletindeki evsizlik tahminlerini içeren bir veri setidir.
- temperatures: Dünyanın dört bir yanındaki şehirlerdeki ortalama sıcaklıkları içeren bir veri setidir. 
- walmart: Her mağaza türünde yapılan toplam benzin satışları içeren bir veri setidir.
---
### *homelessness veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* region: bölge
* state: eyalet
* individuals: bireysel, çocuklu bir ailenin parçası olmayan evsiz bireylerin sayısıdır.
* family_members: çocuklu bir ailenin parçası olan evsiz bireylerin sayısıdır.
* state_pop: eyaletin toplam nüfusu
---
### *walmart veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* store: mağaza 
* type: tür, tip
* department: departman, bölüm
* date: tarih
* weekly_sales: haftalık satışlar
* is_holiday: tatil mi? durumu
* temperature_c: sıcaklık (santigrat)
* fuel_price_usd_per_l: litre başına benzin fiyatları
* unemployment: işsizlik
---
### *avocado veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* date: tarih
* type: tür
* year: yıl
* avg_price: ortalama fiyat
* size: boyutu
* nb_sold: satılan avokado sayısı
---
### *temperatures veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* date: tarih
* city: şehir
* country: ülke
* avg_temp_c: ortalama sıcaklık (santigrat)
---

## License
[MIT](https://choosealicense.com/licenses/mit/)