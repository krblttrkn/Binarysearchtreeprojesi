# Binary Search Tree Projesi

# Proje 3

* **[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
## **[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary Search Tree aşamaları:
```
- Root olarak 6'yı alalım.
  Root=6
- 6'dan küçük olan sayıları 6'nın soluna, 6'dan büyük sayıları 6'nın sağına ekleyeceğim.
- Dizideki ilk sayımız 7'dir. 7 sayısı 6'dan büyük olduğu için 6'nın sağına ekliyorum.
                  6
                    |
                      7       
* Dizide sonraki sayımız 5. 5 sayısı 6'dan küçük olduğu için 6'nın soluna ekliyorum.
                    6
                  |   |
                5       7
* Dizideki sonraki sayımız 1'dir. 1 sayısı 6 dan küçük olduğu için 6'nın soluna eklemeliyim ama 6'nın solunda 5 sayısı var. 1 sayısı 5'ten de küçük olduğu için 1 sayısını 5'in soluna ekliyorum.
                     6
                   |   |
                 5       7
                | 
               1 
*Dizideki sonraki sayımız 8'dir. 8 sayısı 6'dan büyük olduğu için 6'nın sağına ekliyorum. 6'nın sağında 7 var, 8 sayısı 7'den büyük olduğu için 7'nin sağına yazılır.
                        6
                      |   |
                     5      7
                   |          |
                  1             8
*Dizideki sonraki sayımız 3'dir. 3 sayısı 6 dan küçük olduğu için 6'nın soluna ekliyorum. 6'nın solunda 5 var ve 3 sayısı 5'ten küçük olduğu için 3'ü 5'in soluna yazmalıyız. 5'in solunda 1 var ve 1 sayısı 3'ten küçük olduğu için 3'ü 1'in sağına ekliyorum. 
                        6
                      |   |
                     5      7
                   |          |
                  1             8 
                    |
                      3     
*Dizideki sonraki sayımız 0'dır. 0 sayısı 6 dan küçük olduğu için 6'nın soluna ekliyorum. 6'nın solunda 5 var ve 0 sayısı 5'ten küçük olduğu için 0'ı 5'in soluna yazmalıyız. 5'in solunda 1 var ve 0 sayısı 1'den küçük olduğu için 0'ı 1'in soluna ekliyorum.
                           6
                         |   |
                        5      7
                      |          |
                    1             8 
                  |   |
                0       3
*Dizideki sonraki sayımız 9'dur. 9 sayısı 6'dan büyük olduğu için 6'nın sağına ekliyorum. 6'nın sağında 7 var, 9 sayısı 7'den büyük olduğu için 7'nin sağına yazılır. 7'nin sağında 8 var ve 8 sayısı 9'dan küçük olduğu için 9 sayısı 8'in sağına yazılır.
                             6
                           |   |
                          5      7
                        |          |
                       1             8 
                     |   |             |
                   0       3             9
*Dizideki sonraki sayımız 4'tür. 4 sayısı 6 dan küçük olduğu için 6'nın soluna ekliyorum. 6'nın solunda 5 var ve 4 sayısı 5'ten küçük olduğu için 4'ü 5'in soluna yazmalıyız. 5'in solunda 1 var ve 1 sayısı 4'ten büyük olduğu için 4'ü 1'in sağına ekliyorum. 1'in sağında 3 var ve 4 sayısı 3'ten büyük olduğu için 4 3'ün sağına yazılır.                          
                                6
                              |   |
                             5      7
                           |          |
                          1             8 
                        |   |             |
                      0       3             9       
                                |
                                  4
*Dizideki son sayımız 2'dir. 2 sayısı 6 dan küçük olduğu için 6'nın soluna ekliyorum. 6'nın solunda 5 var ve 2 sayısı 5'ten küçük olduğu için 2'yi 5'in soluna yazmalıyız. 5'in solunda 1 var ve 1 sayısı 2'den küçük olduğu için 2'yi 1'in sağına ekliyorum. 1'in sağında 3 var ve 3 sayısı 2'den büyük olduğu için 2'yi 3'ün soluna ekliyorum.
                                 6
                               |   |
                              5      7
                            |          |
                           1             8 
                         |   |             |
                       0       3             9       
                             |   |
                            2     4
```
* **Dipnot** : Biraz fazla açıklayıcı yaptım, amacım kafalarda soru işareti bırakmamak ve bildiklerimin hepsini klavye ile ekranlarınıza yansıtmaktı. Yazılarımla o güzel gözlerinizi yorduğum için kusura bakmayın ve de okuduğunuz için teşekkür ederim:)
-------------------------------------------------------------------------------------
## Patika Profilim:
**[patika linki](https://academy.patika.dev/profile)**
