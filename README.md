# DataStructuresProjects

1) [22,27,16,2,18,6] -> Insertion Sort
a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

   Adım 1: [22,27,16,2,18,6]   , 22 zaten 27'den küçük olduğu değişiklik yok.
   Adım 2: [22,16,27,2,18,6]   , 27 ile 16 yer değişti.
   Adım 3: [16,22,27,2,18,6]   , 22 ile 16 yer değişti.
   Adım 4: [16,22,2,27,18,6]   , 27 ile 2 yer değişti.
   Adım 5: [16,2,22,27,18,6]   , 22 ile 2 yer değişti.
   Adım 6: [2,16,22,27,18,6]   , 16 ile 2 yer değişti.
   Adım 7: [2,16,22,18,27,6]   , 27 ile 18 yer değişti.
   Adım 8: [2,16,18,22,27,6]   , 22 ile 18 yer değişti.
   Adım 9: [2,16,18,22,6,27]   , 27 ile 6 yer değişti.
   Adım 10: [2,16,18,6,22,27]  , 22 ile 6 yer değişti.
   Adım 11: [2,16,6,18,22,27]  , 18 ile 6 yer değişti.
   Adım 12: [2,6,16,18,22,27]  , 16 ile 6 yer değişti.
   
b) Big-O gösterimini yazınız.
  Best Case = O(n) ,Worst Case = (n^2)

c) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1-Average case: Aradığımız sayının ortada olması
2-Worst case: Aradığımız sayının sonda olması
3-Best case: Aradığımız sayının dizinin en başında olması.

  Cevap : 1-Average case: Aradığımız sayının ortada olması.

2) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

    Adım 1: [2,3,5,8,7,9,4,15,6]
    Adım 2: [2,3,4,8,7,9,5,15,6]
    Adım 3: [2,3,4,5,7,9,8,15,6]
    Adım 4: [2,3,4,5,6,9,8,15,7]
    Adım 5: [2,3,4,5,6,7,8,15,9]
    Adım 6: [2,3,4,5,6,7,8,9,15]
   
