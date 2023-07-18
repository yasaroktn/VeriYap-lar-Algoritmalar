## Insertion Sort aşamaları:

[22, 27, 16, 2, 18, 6]

Adım 1: [22, 27, 16, 2, 18, 6] (Başlangıç durumu)
Adım 2: [22, 27, 16, 2, 18, 6] (27, 22'den büyük olduğu için yer değiştirme yok)
Adım 3: [16, 22, 27, 2, 18, 6] (16, 22'den küçük olduğu için 22 ile yer değiştiriyor)
Adım 4: [2, 16, 22, 27, 18, 6] (2, 16'dan küçük olduğu için 16 ile yer değiştiriyor)
Adım 5: [2, 16, 18, 22, 27, 6] (18, 22'den küçük olduğu için 22 ile yer değiştiriyor)
Adım 6: [2, 6, 16, 18, 22, 27] (6, 16'dan küçük olduğu için 16 ile yer değiştiriyor)

Sonuç: [2, 6, 16, 18, 22, 27]

Big-O gösterimi: Insertion Sort'un ortalama ve en kötü durumdaki Big-O gösterimi O(n^2)'dir.

Time Complexity (Zaman Karmaşıklığı):
Dizi sıralandıktan sonra 18 sayısı:

Average case: Dizinin n/2. indeksinde yer alır.
Worst case: Dizinin sonunda yer alır.
Best case: Dizinin başında yer alır.
[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort ilk 4 adımı:

Adım 1: [2, 3, 5, 8, 7, 9, 4, 15, 6] (En küçük eleman olan 2, dizinin başına yerleştirilir)
Adım 2: [2, 3, 5, 8, 7, 9, 4, 15, 6] (3, 2'den büyük olduğu için yer değiştirme yok)
Adım 3: [2, 3, 4, 8, 7, 9, 5, 15, 6] (4, 5'den küçük olduğu için 5 ile yer değiştirir)
Adım 4: [2, 3, 4, 5, 7, 9, 8, 15, 6] (7, 8'den küçük olduğu için 8 ile yer değiştirir)

Sonuç: [2, 3, 4, 5, 7, 9, 8, 15, 6]