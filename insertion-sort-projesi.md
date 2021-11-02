# Insertion Sort Projesi

A. **[22, 27, 16, 2, 18, 6]** -> _Insertion Sort_

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

   - **[2, 27, 16, 22, 18, 6]** -> _2 ile 22 yer değiştirdi._
   - **[2, 6, 16, 22, 18, 27]** -> _6 ile 27 yer değiştirdi._
   - **[2, 6, 16, 22, 18, 27]** -> _16 sağdaki elemanlardan küçük, sabit kalır._
   - **[2, 6, 16, 18, 22, 27]** -> _18 ile 22 yer değiştirdi._
   - **[2, 6, 16, 18, 22, 27]** -> _22 sağdaki elemandan küçük, sıralama sonlandı._

2. Big-O gösterimini yazınız.
   Cevap: **O(n^2)**

3. Time Complexity:
   Cevap:

   - Average case -> **O(n^2)**
   - Worst case -> **O(n^2)**
   - Best case -> **O(n)**

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   Cevap: **Average case** kapsamında.

B. **[7, 3, 5, 8, 2, 9, 4, 15, 6]** dizisinin _Insertion Sort_'a göre ilk 4 adımını yazınız.

1. **[2, 3, 5, 8, 7, 9, 4, 15, 6]** -> _2 ve 7 yer değiştirdi._
2. **[2, 3, 5, 8, 7, 9, 4, 15, 6]** -> _3, sağdaki elemanlardan küçük, sabit kaldı._
3. **[2, 3, 4, 8, 7, 9, 5, 15, 6]** -> _5 ve 4 yer değiştirdi._
4. **[2, 3, 4, 5, 7, 9, 8, 15, 6]** -> _8 ve 5 yer değiştirdi._
