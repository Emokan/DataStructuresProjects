a) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Root : 5
                    5
                /       \
              1           7
             /  \        /   \
            0    3      6      8
                /  \              \
               2    4              9
        
                  
 Adım 1: 7>5 rootun sağ tarafına koyduk.
 Adım 2: 1<5 rootun sol tarafına koyduk.
 Adım 3: 8>5 , 8>7 , 7 nin sağına koyduk.
 Adım 4: 3<5 , 3>1 , 1 in sağına koyduk.
 Adım 5: 6>5 , 6<7 , 7 nin soluna koyduk.
 Adım 6: 0<5 , 0<1 , 1 in soluna koyduk.
 Adım 7: 9>5 , 9>7 , 9>8 , 8 in sağına koyduk.
 Adım 8: 4<5 , 4>3 , 3 ün sağına koyduk.
 Adım 9: 2<5 , 2<3 , 3 ün soluna koyduk.
              
