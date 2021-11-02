# Merge Sort Projesi

**[16, 21, 11, 8, 12, 22]** -> _Merge Sort_

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

   Alt kümelerde birer tane eleman kalana kadar olan ikiye bölme adımları:

   - **[16, 21, 11] | [8, 12, 22]**
   - **[16, 21] | [11] | [8, 12] | [22]**
   - **[16] | [21] | [11] | [8] | [12] | [22]**

   Alt kümeler içerisinde sıralama yaparak alt kümeleri birleştirme adımları:

   - **[16, 21] | [11] | [8, 12] | [22]** -> _16 ve 21 kıyaslandı, 16 küçük olduğu için 1. olarak yazıldı. 8 ve 12 kıyaslandı, 8 küçük olduğu için 1. olarak yazıldı._
   - **[11, 16, 21] | [8, 12, 22]** -> _16 ve 11 kıyaslanır, 11 küçük olduğu başa yazıldı, diğer dizi sıralı olduğu içi kıyaslamaya gerek kalmadı. 8 ve 22 kıyaslandı, 8 küçük olduğu için başa yazıldı, sonra 12 ve 22 kıyaslandı, 12 küçük olduğu için 8'den sonra yazıldı, ardından da 22 yazıldı._
   - **[8, 11, 12, 16, 21, 22]** -> _İki dizideki en küçük sayılar olan 11 ve 8 kıyaslandı, 8 küçük olduğu için başa yazıldı, 11 ve 12 kıyaslandı, 11 küçük olduğu için 2. olarak yazıldı, 16 ve 12 kıyaslandı, 12 küçük olduğu için 3. olarak yazıldı, 16 ve 22 kıyaslandı, 16 küçük olduğu için 4. olarak yazıldı, 21 ve 22 kıyaslandı, 21 küçük olduğu için 5. olarak yazıldı, dizideki tek eleman 22 kaldığı için 6. olarak yazıldı._

2. Big-O gösterimini yazınız.
   Cevap: **O(nlogn)**
