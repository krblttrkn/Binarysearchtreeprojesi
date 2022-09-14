# Binary Search Tree Projesi

# Proje 3

* **[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
## **[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary Search Tree aşamaları:
- Root olarak 6'yı alalım.<br>
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
*