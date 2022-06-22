# Proje 2
## Merge Sort Project
[16,21,11,8,12,22] -> Merge Sort

Soru 1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Soru 2: Big-O gösterimini yazınız.

- Cevap 1: dizinin sort türüne göre aşamaları
1. [16, 21, 11] [8, 12, 22]
2. [16, 21] [11] [8, 12] [22]
3. [16] [21] [11] [8] [12] [22]
4. [11] [16] [21] [8] [12] [22]
5. [11, 16, 21] [8, 12, 22]
6. [8, 11, 12, 16, 21, 22]

- Cevap 2: Big-O gösterimi

O(nlogn) = O(6log6)