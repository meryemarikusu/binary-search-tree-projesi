## Binary Search Tree Projesi

***[7,5,1,8,3,6,0,9,4,2] dizisinin binary search tree aşamalarını yazınınz.***

- Binary search tree'de bir düğüm her iki tarafa da referans verebiliyor. Root'a göre sağ tarafında kendinden büyük elemanlar, sol tarafında kendinden küçük elemanlar olur.

- Root 5'e göre sayı dizisindeki elemanlara sırasıyla baktığımızda binary search tree aşamaları şu şekilde oluşturulur:

- 7>5'ten 5'in sağına 7 yazılır.
- 1<5'ten 5'in soluna 1 yazılır.
- 8>5'ten 5'in sağına gidilir; 8>7'den 7'nin sağına 8 yazılır.
- 3<5'ten 5'in soluna gidilir; 3>1'den 1'in sağına 3 yazılır.
- 6>5'ten 5'in sağına gidilir; 6<7'den 7'nin soluna 6 yazılır.
- 0<5'ten 5'in soluna gidilir. 0<1'den 1'in soluna 0 yazılır.
- 9>5'ten 5'in sağına gidilir; 9>7'den 7'nin sağına gidilir; 9>8'den 8'in sağına 9 yazılır.
- 4<5'ten 5'in soluna gidilir; 4>1'den 1'in sağına gidilir; 4>3'ten 3'ün sağına 4 yazılır.
- 2<5'ten 5'in soluna gidilir; 2>1'den 1'in sağına gidilir; 2<3'ten 3'ün soluna 2 yazılır.

                    5
                 /     \ 
                1        7
              /   \    /  \
             0    3   6    8
                /   \        \
               2     4        9
           
[Patika Dev](https://app.patika.dev/meryemarikusu)
