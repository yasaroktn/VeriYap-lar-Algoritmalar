## Merge Sort aşamaları:

[16, 21, 11, 8, 12, 22]

Adım 1: [16, 21, 11] ve [8, 12, 22] olarak ikiye bölünür.
Sol yarı dizisi: [16, 21, 11]
Sağ yarı dizisi: [8, 12, 22]

Adım 2: Sol yarı dizisi olan [16, 21, 11] tekrar ikiye bölünür.
Sol yarı dizisi: [16]
Sağ yarı dizisi: [21, 11]

Adım 3: Sağ yarı dizisi olan [21, 11] tekrar ikiye bölünür.
Sol yarı dizisi: [21]
Sağ yarı dizisi: [11]

Adım 4: Sol yarı dizisi olan [21] ve sağ yarı dizisi olan [11] birleştirilerek sıralanır.
Birleştirilmiş dizi: [11, 21]

Adım 5: Sağ yarı dizisi olan [8, 12, 22] tekrar ikiye bölünür.
Sol yarı dizisi: [8]
Sağ yarı dizisi: [12, 22]

Adım 6: Sağ yarı dizisi olan [12, 22] tekrar ikiye bölünür.
Sol yarı dizisi: [12]
Sağ yarı dizisi: [22]

Adım 7: Sol yarı dizisi olan [12] ve sağ yarı dizisi olan [22] birleştirilerek sıralanır.
Birleştirilmiş dizi: [12, 22]

Adım 8: Sol yarı dizisi olan [16] ve sağ yarı dizisi olan [11, 21] birleştirilerek sıralanır.
Birleştirilmiş dizi: [11, 16, 21]

Adım 9: Sol yarı dizisi olan [11, 16, 21] ve sağ yarı dizisi olan [8, 12, 22] birleştirilerek sıralanır.
Birleştirilmiş dizi: [8, 11, 12, 16, 21, 22]

Sonuç: [8, 11, 12, 16, 21, 22]

Big-O gösterimi: Merge Sort'un Big-O gösterimi O(n log n)'dir.