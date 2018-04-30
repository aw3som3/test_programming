// soal test algoritma

1. pohon keluarga

   var keluarga = [
		{id:1,parentId:null,nama:"ahmad"},
		{id:2,parentId:1,nama:"wisnu"},
		{id:3,parentId:1,nama:"asna"},
		{id:4,parentId:2,nama:"danu"},
		{id:5,parentId:2,nama:"dani"},
		{id:6,parentId:3,nama:"kali"},
		{id:7,parentId:3,nama:"kalo"},
		{id:8,parentId:4,nama:"jona"},
		{id:9,parentId:7,nama:"joni"}
   ];
   
   berdasarkan data diatas tampilkan pohon keluarga sebagai berikut
   
	-ahmad
	--wisnu
	---danu
	----jona
	---dani
	--asna
	---kali
	---kalo
	----joni
				
2. sorting
	[1,3,4,2,3,6,7,4,3,2,5,8,9]
	
	urutkan array tersebut berdasarkan kriteria sbb
	1. genap lebih dulu daripada ganjil
	2. besar ke kecil
	
	ekspektasi hasil : [8,6,4,4,2,2,9,7,5,3,3,3,1]
