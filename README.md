# Veri-yapilari-ve-Algoritmalar

// Proje 1 --> Insertion Sort Projesi
 
1-) [22,27,16,2,18,6]-> Insertion Sort

  [2,27,16,22,18,6]  n-1

  [2,6,16,22,18,27]  n-2

  [2,6,16,18,22,27] 1

  n+(n-1)+(n-2)+...+1 == (n*(n+1))/2

2-)  Big O --> O(n^2)

3-) Average Case : 16,2
    Best Case : 22
    Worst Case : 6

4-) Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer. 

  [7,3,5,8,2,9,4,15,6]-->Insertion sorta göre ilk 4 adımı:
 
  [2,3,5,8,7,9,4,15,6]  n-1    
  
  [2,3,4,8,7,9,5,15,6]  n-2
  
  [2,3,4,5,7,9,8,15,6]  n-3
  
  [2,3,4,5,6,9,8,15,7]  n-4
 

// Proje 2 --> Merge Sort Projesi

[16,21,11,8,12,22]

[16,21,11]          [8,12,22]

[16] [21,11]        [8,12]  [22]

[16] [11,21]        [8,12]  [22]

[11,16,21]          [8,12,22]

    [8,11,12,16,21,22]
    
 Big-O --> O(nlogn)
 
 
 // Proje 3 --> Binary Search Tree Projesi
 
 [7,5,1,8,3,6,0,9,4,2] 
 
 Root 7'dir. Rootun sağında 8 solunda 5 bulunur.
 
 8'in sağında 9 bulunur.
 
 5'in sağında 6,solunda 1 bulunur.
 
 1'in solunda 0 sağında 3 bulunur.
 
 3'ün solunda 2 bulunur.
  
 6'nın solunda 4 bulunur.
 
