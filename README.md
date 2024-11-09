# SEMANTIC-HTML
Nama : Danang Eko Prasetyo
Nim  : 2205101150
Kelas: 5A


### HASIL ANALISIS ###
1. Kesalahan pada Definisi grid-template-areas: Pada bagian CSS:
   grid-template-areas:
     "header header header"
     "nav section section"
     "footer footer footer"
     grid-template-rows: 80px 1fr 50px;
     grid-template-columns: 20% 1fr 18%;
   Tidak ada tanda titik koma (;) setelah grid-template-areas, sehingga ini akan memicu error pada CSS. Perbaiki dengan tanda titik koma setelah grid-template-areas
     grid-template-areas:
       "header header header"
     "nav section section"
     "footer footer footer";
