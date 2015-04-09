---
layout: post
title: Siyah beyaz televizyonlar
---

Hepinizin bildiği gibi ilk televizyonlar siyah beyazdı. Dış dünyanın renkli halini bir display yardımıyla siyah-beyaz gösterip, renkli hayal ettirmek zorundaydınız. RGB renk uzayını siyah-beyaz hale dönüştürmek için bir değişkene ihtiyacımız var. 3 renkten hareketle siyah-beyaz yani grinin tonlarını elde etmeliyiz. Buna Y denilmiş (Luminance). Parlaklık gibi düşünebiliriz. 

Gözümüz çok ilginç bir yapıya sahip. Yeşil, Kırmızı ve Mavi renklerde ışık veren kaynaklarımız olsa ve biz belli bir mesafeden bunlara bakıyor olsak bu kaynakların ışık miktarını eşit şekilde yavaş yavaş arttırsak gözümüz ilginç bir şekilde üçü eşit miktarda olmasına rağmen önce yeşili görüyor. Aradan biraz zaman geçiyor sonra kırmızıyı, baya bi zaman geçiyor ve maviyi görüyor. Yani renklere eşit davranmıyor. Bu oranlar yaklaşık olarak şöyle formülize edilmiş: %70 yeşile önem veriyor, %20 kırmızıya, %10 maviye. Buradan hareketle RGB kanallarının hangi kaysayılarla çarpılması gerektiği bulunmuş. Bu katsayılar şu şekilde:

<div class="message">
  Y =  0.2215*R + 0.7154*G + 0.0721*B
</div>

yeşil kanalını 0.7154 ile, kırmızıyı 0.2215, maviyi 0.0721 ile çarp, topla denilmiş. Üçü de eşit miktarda alınıp üçe bölünmemiş. Eğer böyle yapılsaydı dış dünyadan alınan görüntünün siyah beyaz karşılığını yadırgayacaktık. Beynimiz eksik parçaları tamamlamaya çalışacaktı ve televizyon izlemek yorucu bir hal alacaktı...

Bu şekilde 3 boyutlu renkli dünyamızı grileştirdik ve o halde ekranda göstermeye başladık. Bu katsayılar sayesinde de farkında olmayarak bilinç altımızda her şeyi renklendirdik, yadırgamadık :)