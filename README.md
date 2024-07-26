# Binary-Search-Tree-a-amalar-Proje-3
Kodluyoruz Eğitimi kapsamında [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları Proje 3
## 1. 7 ekle: Kök düğüm olarak 7
  7
## 2. 5 ekle: 5, 7'den küçük olduğu için 7'nin soluna eklenir.
          7
         /
        5
## 3. 1 ekle: 1, 7'den küçük olduğu için sol alt ağaçta yer alacak, sonra 5'ten de küçük olduğu için 5'in soluna eklenir.
             7
            /
           5
          /
        1
        
## 4. 8 ekle: 8, 7'den büyük olduğu için sağ alt ağaçta yer alacak, bu yüzden 7'nin sağına eklenir.
             7
            /  \
           5    8
          /
        1
## 5. 3 ekle: 3, 7'den küçük olduğu için sol alt ağaçta yer alacak, 5'ten de küçük, 1'den büyük olduğu için 1'in sağına eklenir.
               7
             /   \
           5      8
          / 
        1   
          \ 
            3
## 6. 6 ekle: 6, 7'den küçük olduğu için sol alt ağaçta yer alacak, 5'ten büyük olduğu için 5'in sağına eklenir.
               7
             /   \
           5      8
          /   \
        1      6 
          \ 
            3
## 7. 0 ekle: 0, 7'den küçük olduğu için sol alt ağaçta yer alacak, 5'ten de küçük, 1'den de küçük olduğu için 1'in soluna eklenir.
               7
             /   \
           5      8
          /   \
        1      6 
      /    \ 
     0      3
## 8. 9 ekle: 9, 7'den büyük olduğu için sağ alt ağaçta yer alacak, 8'den de büyük olduğu için 8'in sağına eklenir.
               7
             /   \
           5      8
          /   \    \  
        1      6    9
      /    \ 
     0      3

## 9. 4 ekle: 4, 7'den küçük olduğu için sol alt ağaçta yer alacak, 5'ten de küçük, 1'den büyük, 3'ten büyük olduğu için 3'ün sağına eklenir.
               7
             /   \
           5      8
          /   \    \  
        1      6    9
      /    \ 
     0      3
             \
              4
  ## 10. 2 ekle: 2, 7'den küçük olduğu için sol alt ağaçta yer alacak, 5'ten de küçük, 1'den büyük, 3'ten küçük olduğu için 3'ün soluna eklenir.

               7
             /   \
           5      8
          /   \    \  
        1      6    9
      /    \ 
     0      3
          /  \
         2    4

