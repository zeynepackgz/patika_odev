# Merge Sort Projesi

## Dizi: [16, 21, 11, 8, 12, 22]

---

## 🔄 Merge Sort Aşamaları:

**Bölme (Divide):**

1. [16, 21, 11, 8, 12, 22]  
2. [16, 21, 11], [8, 12, 22]  
3. [16], [21, 11] → [21], [11]  
4. [8], [12, 22] → [12], [22]  

**Sıralama ve Birleştirme (Conquer & Merge):**

5. [21], [11] → [11, 21]  
6. [16], [11, 21] → [11, 16, 21]  
7. [12], [22] → [12, 22]  
8. [8], [12, 22] → [8, 12, 22]  
9. [11, 16, 21], [8, 12, 22] → **[8, 11, 12, 16, 21, 22]**

---

## 📊 Big-O Gösterimi:

- **Best Case:** O(n log n)
- **Average Case:** O(n log n)
- **Worst Case:** O(n log n)

> Merge Sort her durumda sabit olarak n log n zaman karmaşıklığına sahiptir. Bölme ve birleştirme aşamaları tüm verilerde çalışır.
