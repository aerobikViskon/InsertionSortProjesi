# InsertionSortProjesi


Verilen dizi: `[22, 27, 16, 2, 18, 6]`

**Aşama 1:**
- İlk eleman (22) sıralıdır, başka bir işlem yapılmaz.
  - Dizi: `[22, 27, 16, 2, 18, 6]`

**Aşama 2:**
- 27 elemanı yerinde kalır çünkü 27 > 22.
  - Dizi: `[22, 27, 16, 2, 18, 6]`

**Aşama 3:**
- 16 sayısı 27'yi geçer ve 22 ile yer değiştirir.
  - Dizi: `[16, 22, 27, 2, 18, 6]`

**Aşama 4:**
- 2 sayısı, 27, 22, 16'yı geçer ve başa yerleşir.
  - Dizi: `[2, 16, 22, 27, 18, 6]`

**Aşama 5:**
- 18 sayısı, 27'yi geçer ve yerine yerleşir.
  - Dizi: `[2, 16, 18, 22, 27, 6]`

**Aşama 6:**
- 6 sayısı, 27, 22, 18, 16 ve 2'yi geçer ve başa yerleşir.
  - Dizi: `[2, 6, 16, 18, 22, 27]`

**Sonuç:**
- Sıralanmış Dizi: `[2, 6, 16, 18, 22, 27]`

### Big-O Gösterimi
- **Best case (dizi zaten sıralı):** O(n)
- **Worst case (ters sıralı dizi):** O(n²)
- **Average case:** O(n²)

### Time Complexity
- **Worst Case (En kötü durum):** O(n²)
- **Best Case (En iyi durum):** O(n)

**18 sayısı hangi case'e girer?**
- 18 sayısı, sıralandıktan sonra dizinin ortasında olduğu için **Average Case** kapsamına girer.

---

### 2. Selection Sort ile İlk 4 Adım

Verilen dizi: `[7, 3, 5, 8, 2, 9, 4, 15, 6]`

**Aşama 1:**
- En küçük eleman 2'dir. 2, 7 ile yer değiştirir.
  - Dizi: `[2, 3, 5, 8, 7, 9, 4, 15, 6]`

**Aşama 2:**
- 3 zaten yerindedir, en küçük eleman 3'tür.
  - Dizi: `[2, 3, 5, 8, 7, 9, 4, 15, 6]`

**Aşama 3:**
- En küçük eleman 4'tür. 4, 5 ile yer değiştirir.
  - Dizi: `[2, 3, 4, 8, 7, 9, 5, 15, 6]`

**Aşama 4:**
- En küçük eleman 5'tir. 5, 8 ile yer değiştirir.
  - Dizi: `[2, 3, 4, 5, 7, 9, 8, 15, 6]`

---

## Özet

- **Insertion Sort** algoritması, her bir öğeyi sırasıyla doğru yerine yerleştirir. En kötü durum O(n²), en iyi durum O(n)'dir.
- **Selection Sort** algoritması ise her adımda dizinin en küçük öğesini bulur ve yer değiştirir. İlk 4 adımda her defasında en küçük elemanı bulur ve takas yapar.
