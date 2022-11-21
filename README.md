# Magaza Yorumlari Sementic Analysis
![image](https://www.yasantipsikoloji.com/upload/images/sayfalar/2020/duygusal-problemleri-cozmenin-10-yolu-44069-5315495833-t.jpg)

* Data were collected in Turkish from various electronic stores.
*The distinction of emotion is divided into three as "Olumlu", "Olumsuz" ve "Tarafsız".
  * If costumer review Olumsuz = "0"
  * If costumer review Olumlu = "1"  
  * If costumer review Tarafsız = "2"

## Steps:
1. Data is read.
2. Data and information are analyzed in detail.
3. The data["Durum"] part is visualized from the data.
4. Missing values are found. Missing values are deleted.
5. The model is trained with the bert algorithm.

## Conclusion

|index|Görüş|Durum|Sementic|Probability|
|-----|-----|----|----|-----|
|0|ses kalitesi ve ergonomisi rezalet, sony olduğu için aldım ama 4'de 1 fiyatına çin replika ürün alsaydım çok çok daha iyiydi, kesinlikle tavsiye etmiyorum.|0|negative|0.999512|
|1|hizli teslimat tesekkürler|2|positive|0.795702|
|2|ses olayı süper....gece çalıştır sıkıntı yok.....kablo uzun işinizi çok rahat ettirir.....çekme olayı son derece güzel içiniz rahat olsun......diğerlerini saymıyorum bile.....|1|positive|0.988502|
|3|geldi bigün kullandık hemen bozoldu hiçtavsiye. etmem|0|negative|0.997646|
|4|Kulaklığın sesi kaliteli falan değil. Aleti öve öve bitiremeyen yorumlar şüpheli. Tizler yok gibi ve olan da boğuk çıkıyor. Bas, kaba saba, ben buradayım diyor ama kalite yok. İyi ses arayanlara tavsiye etmem. Hayatımda aldığım ilk Snopy marka üründü, onu da bazı yorumlara güvenerek aldım ve pişman oldum. Hepsiburada'nın sahte yorumlara karşı önlem alması gerekiyor artık.|0|negative|0.998313|
