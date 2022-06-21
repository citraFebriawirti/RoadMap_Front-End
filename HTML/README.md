# HTML
  A. Paragraf Html
  --> digunakan untuk penulisan kalimat dalam bentuk paragraf dengan   menggunakan sintaks
  ``<p>....</p>``
  
  B. Heading
  --> digunakan untuk penulisan judul dengan urutan ukuran dari
  ``<h1>....</h1>``
   ``<h2>....</h2>``
    ``<h3>....</h3>``
     ``<h4>....</h4>``
      ``<h5>....</h5>``
       ``<h6>....</h6>``
       
   C. List
   --> digunakan untuk urutan dari daftar yang terstruktur atau tidak terstruktur
   1. unoderlist (tidak memiliki urutan)
   
       ``` 
       <ul>
            <li>Item 1</li>
            <li>Item 2</li>
        </ul> 
         ````
         hasil :
          <ul>
            <li>Item 1</li>
            <li>Item 2</li>
         </ul> 
         
   2. oderlist (memiliki urutan)
   
       ``` 
       <ol type="1">
            <li>Item 1</li>
            <li>Item 2</li>
        </ol> 
         ````
         hasil :
          <ol type="1">
            <li>Item 1</li>
            <li>Item 2</li>
         </ol> 
   
  
   D. Teks format
   
   1. long quotations adalah sebuah paragraf, heading ataupun list
  
       ```
        <blockquote>
          <p>nama saya adalah sakura</p>
        </blockquote>
        ````
        hasil :
       <blockquote>
          <p>nama saya adalah sakura</p>
        </blockquote>
    
  2. pre adalah line breaks untuk baris baru
        ```
        <pre>
           Senja
           
           sudah tampak di ujung mata 
           kau pergi dalam kehangatan
           dirimu datang hanya sementara
           diantara cerianya alam yang menerpa
        </pre>
        ````
        hasil :
        <pre>
           Senja
           
           sudah tampak di ujung mata 
           kau pergi dalam kehangatan
           dirimu datang hanya sementara
           diantara cerianya alam yang menerpa
        </pre>
        
   3. Figure adalah elemen yang digunakan untuk gambar
        ```
        <figure>
          <img src="https://media.suara.com/pictures/653x366/2022/06/10/10967-digital-talent-readiness-menjadi-salah-satu-bagian-tes-pt-telkom-telkom.webp" width="150px">
          <figcaption>telkom</figcaption>
        </figure>
        ````
        hasil :
        <figure >                                                              <img src="https://media.suara.com/pictures/653x366/2022/06/10/10967-digital-talent-readiness-menjadi-salah-satu-bagian-tes-pt-telkom-telkom.webp" width="300px"><br>
          <figcaption>telkom</figcaption>
        </figure>
  
   E. Jenis Gambar

   <table border="1" cellpadding="10">
        <tr>
            <td>Format</td>
            <td>.jpg, .jpeg, .jfif, .pjpeg, .pjp</td>
            <td>.png,.svg</td>
        </tr>
        <tr>
            <td>Keterangan</td>
            <td>kualitas gambar dapat menjadi buruk</td>
            <td>kualitas gambar menjadi baik dan terbaca</td>
        </tr>
    </table>
        
    
