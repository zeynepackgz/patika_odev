# 🌳 Binary Search Tree Projesi

## 🎯 Amaç
Verilen bir sayı dizisinden Binary Search Tree (İkili Arama Ağacı) oluşturmak ve her bir adımda düğümlerin ağaçta nerede yer aldığını göstermek.

---

## 🔢 Verilen Dizi


---

## 🧱 Binary Search Tree Oluşturma Aşamaları

1. 7 → Root (kök) olur.
2. 5 → 5 < 7 → Soluna eklenir.
3. 1 → 1 < 7 → Sol, 1 < 5 → Sol → 1, 5'in soluna eklenir.
4. 8 → 8 > 7 → Sağ → 8, root'un sağına eklenir.
5. 3 → 3 < 7 → Sol, 3 < 5 → Sol, 3 > 1 → Sağ → 3, 1'in sağına eklenir.
6. 6 → 6 < 7 → Sol, 6 > 5 → Sağ → 6, 5'in sağına eklenir.
7. 0 → 0 < 7 → Sol, 0 < 5 → Sol, 0 < 1 → Sol → 0, 1'in soluna eklenir.
8. 9 → 9 > 7 → Sağ, 9 > 8 → Sağ → 9, 8'in sağına eklenir.
9. 4 → 4 < 7 → Sol, 4 < 5 → Sol, 4 > 1 → Sağ, 4 > 3 → Sağ → 4, 3'ün sağına eklenir.
10. 2 → 2 < 7 → Sol, 2 < 5 → Sol, 2 > 1 → Sağ, 2 < 3 → Sol → 2, 3'ün soluna eklenir.

---

## 🌲 Ağaç Yapısı

        7
      /   \
     5     8
    / \     \
   1   6     9
  / \
 0   3
    / \
   2   4

---

## 🧠 Açıklama Cümleleriyle

- **Root**: 7'dir.
- 7'nin **solunda 5**, **sağında 8** bulunur.
- 5'in solunda **1**, sağında **6** bulunur.
- 1'in solunda **0**, sağında **3** bulunur.
- 3'ün solunda **2**, sağında **4** bulunur.
- 8'in sağında **9** bulunur.

---

## 💡 Not
Bu proje, veri yapıları dersi kapsamında Binary Search Tree mantığını kavramak amacıyla hazırlanmıştır.
