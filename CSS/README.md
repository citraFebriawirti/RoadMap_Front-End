# CSS
A. Selector Basic
1. Type Selector 
   --> menggunakan nama elemen sebagai target
   ```
   h1 {
      color : green;
    }

2. class selector 
   --> menetapkan target elemen berdasarkan nilai dari atribut kelas
   ```
   .container{
            color : red;
     }
3. ID Selector
   --> menetapkan target elemen berdasarkan nilai dari atribut ``id``
   ```
   #main{
      color : blue;
    }
    
4. Attribute Selector
   --> menetapkan target elemen berdasarkan yang lebih spesifik
   ```
   a[href]{
         color : red;
   }
5. Universal Selector 
  --> diterapkan pada seluruh elemen
  ```
  * {
  color : red;
   }
  ````
   
B. Combinators
   1. adjecent sibling selector(+)
   --> menggabungkan dua buah basic selector dengan mengggunakan tanda + diantara keduanya, namun hanya menerapkan pada elemen kedua.
   ```
   img + p {
          color : green;
   }
   ````
   
  2. General Sibling selector (~)
    --> menerapkan pada seluruh elemen setelah elemen pertama
      ```
       img ~ p {
             color : green;
          }
      ```
    
   3. Descendant Selector (space)
   --> basic selector pertama ditulis sebagai induk, basic selector kedua yang akan menerapkan rule.
   ```
   div p {
      color : red;
    }
   ````
   
  C. Pseudo-Class
  1.  Pseudo-class selector
  
   ```
   
      /* rule akan diterapkan pada sebuah tautan yang belum pernah  dikunjungi */
      a:link {
         color: red;
      }
 
    /* rule akan diterapkan pada sebuah tautan yang sudah pernah dikunjungi */
      a:visited {
         color: green;
      }
 
    /* rule akan diterapkan pada sebuah tautan ketika diarahkan dengan kursor */
      a:hover {
         color: pink;
      }
 
    /* rule akan diterapkan pada sebuah tautan ketika ditekan */
      a:active {
         color:orange;
      }
   ```
   
   2. pseudo-elemen selector
   --> ``::before`` , ``::after``
   
   
   D. Box-Shadow
   --> untuk memberikan shadow pada box agar kelihatan 3d
   ```
   box-shadow:rata_atas_bawah rata_kiri_kanan jarak_bayangan ketebalan_bayangan warna;
   ````

  E. Display <br>
 
     1. Display : none -> digunakan untuk menyembunyikan elemen serta berpengaruh terhadap elemen disekitarnya <br>
     2. Visibility : hidden -> digunakan untuk menyembunyikan element tetapi tidak berpengaruh terhadap elemen disekitarnya <br>
  
    
