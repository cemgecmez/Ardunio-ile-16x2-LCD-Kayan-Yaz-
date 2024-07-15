# Ardunio-ile-16x2-LCD-Kayan-Yazi-
Gerekli Malzemeler
• Ardunio Uno Geliştirme Kartı
• 1 adet 16x2 LCD Ekran (HD44780 veya KS0066)
• 1 adet 10kΩ potansiyometre
• 3 adet buton
• 3 adet 4.7 KΩ direnç

Adımlar

1) 16x2 LCDnizi seçmiş olduğunuz kontrolcüsünün (HD44780 veya KS0066) pin yapısına
göre 4 bitlik veri iletişim modu olacak şekilde gerekli bağlantılarını Arduino kartınız ile
yapınız.

2) 16x2 LCDnizin data hattı dışında gerekli diğer bağlantılarını yapınız.

3) 3 adet butonu 4.7 KΩ dirençler ile birlikte uygun boş pinlere bağlayınız ve bağlantı
şemanızı raporunuza mutlaka ekleyiniz. Butonlarınızı breadboard üzerinde
pozisyonlarken yan yana konumlayınız. Bundan sonra butonlar pozisyonları ile
isimlendirilecektir.

4) LCD’nizin üst satırında büyük harfler ile “KKU MMF EEM” alt satırında öğrenci
numaranız ile birlikte DEN 2 ifadesi olacaktır. Örnek “180204999 DEN 2”. Metinler
LCD ekranın ortasında ortalı şekilde olacaktır.

5) Sol butona her basıldığında metin bulunduğu konumdan 1 kolon sola kayacaktır. Sağ
butona basıldığında ise metin bulunduğu konumdan 1 kolon sağa kayacaktır. Orta
butona basıldığında ise metin başlangıç pozisyonu olan LCD’nin ortasına gelecektir.
