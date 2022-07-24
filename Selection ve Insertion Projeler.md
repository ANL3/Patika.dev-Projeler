# Patika.dev-Projeler
 Veri Yapıları ve Algoritmalar - Proje 1

## Selection Sort

### Aşamalar (22 27 16  2 18  6)

  2 27 16 22 18  6
 
  2  6 16 22 18 27
 
  2  6 16 22 18 27
 
  2  6 16 18 22 27
 
  2  6 16 18 22 27
 
### Big O Gösterimi (Worst Case)
 
 (n-1) + (n-2) + ... + 1 = (n-1)*n/2 ---> O(n^2)
 
 Algoritma tüm durumlar için benzer şekilde işleyecektir. Big O gösterimleri aynı olacaktır.
 
### Time Complexity (18 için)
 
 Aradığımız sayı ortada olduğu için Avarage Case kapsamına girer.
 
## Insertion Sort
 
### Aşamalar (22 27 16  2 18  6)
 
 22 27 16  2 18  6
 
 16 22 27  2 18  6
 
  2 16 22 27 18  6
 
  2 16 18 22 27  6
  
  2  6 16 18 22 27
  
### Big O Gösterimi (Worst Case)

 Insertion için ilk eleman işleme girmez. İkinci eleman ilk elemanla işleme girer. Yani bir işlem yapılır. Üçüncü eleman önündeki iki elemanla işleme girer. Yani iki işlem yapılır. Bu şekilde n. eleman için n-1 işlem yapılmaktadır.
 
 1 + 2 + ... + (n-1) = (n-1)*n/2 ---> O(n^2)

### Big O Gösterimi (Best Case)

 Insertion için ilk eleman işleme girmez. İkinci eleman ilk elemanla işleme girer. Yani bir işlem yapılır. Üçüncü eleman önündeki elemanla işleme girer. Yani yine bir işlem yapılır. Bu şekilde n. eleman için de bir işlem yapılır.
 
 1 + 1 + ... + 1 = n ---> O(n)
 
 ### Time Complexity (18 için)
 
 Aradığımız sayı ortada olduğu için Avarage Case kapsamına girer.
 
 www.patika.dev
