>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---
* Root olarak 8'i seçtik.
* 6'yı ekleyeceğiz, 8'den küçük olduğu için root'un soluna yerleştiririz.
* 9'u ekleyeceğiz, 8'den büyük olduğu için root'un sağına yerleştiririz.
* 3'ü ekleyeceğiz, root'un soluna gittik, ilk node olan 6'ya sorduk, 6'dan küçük olduğu için soluna yerleştiririz.
* 7'yi ekleyeceğiz, root'un soluna gittik, 6'ya sorduk, 6'dan büyük olduğu için sağına yerleştiririz.
* 5'i ekleyeceğiz, root'un soluna gittik, 6'dan küçük olduğu için soluna gittik, 3'ten büyük olduğu için sağına yerleştiririz.
* 1'i ekleyeceğiz, root'un soluna gittik, 6'dan küçük olduğu için soluna gittik, 3'ten küçük olduğu için soluna yerleştiririz.
* 2'yi ekleyeceğiz, root'un soluna gittik, 6'dan küçük olduğu için soluna gittik, 3'ten küçük olduğu için soluna gittik, 1'den büyük olduğu için sağına yerleştiririz.
* 4'ü ekleyeceğiz, root'un soluna gittik, 6'dan küçük olduğu için soluna gittik, 3'ten büyük olduğu için sağına gittik, 5'ten küçük olduğu için soluna yerleştiririz.




            8
           / \
          6   9
         / \
        3   7
      /  \
     1    5
      \   /
       2 4
