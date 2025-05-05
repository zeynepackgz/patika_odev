# Insertion Sort Projesi

### Dizi: [22, 27, 16, 2, 18, 6]

#### **Adım 1:** İlk eleman (22) kendi yerinde kalır.

Yeni dizi: [22, 27, 16, 2, 18, 6]

#### **Adım 2:** 27 ile 22 karşılaştırılır. 27 büyük olduğu için değişmez.

Yeni dizi: [22, 27, 16, 2, 18, 6]

#### **Adım 3:** 16 ile 27 karşılaştırılır. 16 küçük olduğu için 27 bir pozisyon sağa kaydırılır, sonra 16 ile 22 karşılaştırılır. 16 küçük olduğu için 22 bir pozisyon sağa kaydırılır. 16 dizinin başına yerleşir.

Yeni dizi: [16, 22, 27, 2, 18, 6]

#### **Adım 4:** 2 ile 27, 22 ve 16 karşılaştırılır. 2 dizinin en başına yerleşir, diğer tüm elemanlar birer pozisyon sağa kaydırılır.

Yeni dizi: [2, 16, 22, 27, 18, 6]

#### **Adım 5:** 18 ile 27 karşılaştırılır. 18 daha küçük olduğu için 27 bir pozisyon sağa kaydırılır, 22 ile karşılaştırılır ve 18 küçük olduğu için 22 bir pozisyon sağa kaydırılır, 16 ile karşılaştırılır ve 18 küçük olduğu için 16 bir pozisyon sağa kaydırılır. 18 dizinin 2. pozisyonuna yerleşir.

Yeni dizi: [2, 16, 18, 22, 27, 6]

#### **Adım 6:** 6 ile 27, 22, 18, 16 ve 2 karşılaştırılır. 6 dizinin 3. pozisyonuna yerleşir.

Yeni dizi: [2, 6, 16, 18, 22, 27]

### Big-O Gösterimi

- **Best Case (En İyi Durum)**: O(n)
- **Worst Case (En Kötü Durum)**: O(n²)
- **Average Case (Ortalama Durum)**: O(n²)

### 18 Sayısı İçin Durumlar

- **Best Case**: 18, dizinin başında olsaydı.
- **Average Case**: 18, dizinin ortasında.
- **Worst Case**: 18, dizinin sonunda olsaydı.

---

### Selection Sort Aşamaları

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

**Adım 1:** Dizideki en küçük eleman 2'dir. 2 ile 7 yer değiştirir.

Yeni dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

**Adım 2:** Kalan dizideki en küçük eleman 3'tür. 3 ile 3 yer değiştirir, dolayısıyla dizi değişmez.

Yeni dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

**Adım 3:** Kalan dizideki en küçük eleman 4'tür. 4 ile 5 yer değiştirir.

Yeni dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]

**Adım 4:** Kalan dizideki en küçük eleman 5'tir. 5 ile 8 yer değiştirir.

Yeni dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]
