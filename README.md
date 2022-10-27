# Nama : Naza Sefti Prianita
# Nim  : 312210306
# Kelas: TI.22.A3

# Latihan 1

# Penggunaan end

![Screenshot (51)](https://user-images.githubusercontent.com/115772516/198219512-54127900-4022-4aa3-81fe-9573b914cd28.png)

# Penggunaan separator

# String format 1

![Screenshot (53)](https://user-images.githubusercontent.com/115772516/198220340-18c23df9-f996-44f7-a0dc-299b2f4a922d.png)

# String format 2

![Screenshot (55)](https://user-images.githubusercontent.com/115772516/198220649-35d6ba5c-432d-445e-b52b-64e896b9ef57.png)

# Hasil latihan 1

![Screenshot (57)](https://user-images.githubusercontent.com/115772516/198221441-b0efb6bf-b4a7-41c7-a72d-5118147b37b1.png)

![Screenshot (58)](https://user-images.githubusercontent.com/115772516/198221841-91ce86d3-139c-4490-ade1-bb154a67a1f8.png)

# Latihan 2

# Masukkan variable

![Screenshot (60)](https://user-images.githubusercontent.com/115772516/198222357-14719ac4-b5f6-43b3-ad56-808e06484c71.png)

# Konversi nilai variable

![Screenshot (61)](https://user-images.githubusercontent.com/115772516/198222681-8e90e20c-97c0-495c-9c27-eac39ff5dec0.png)

# Hasil latihan 2

![Screenshot (63)](https://user-images.githubusercontent.com/115772516/198223134-f2e2a43f-9b52-4b14-9f08-f0c39ef60719.png)

# Latihan 3

# String kode belah ketupat
string = ""

x = int(input("Masukkan angka :"))
bar = x
# Looping Baris
while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri		
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1		
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1	

	string = string + "\n\n"
	bar = bar - 1

bar = 1	
# Looping Baris
while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri	
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1	
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri	
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
print (string)

# Hasil belah ketupat

![Screenshot (65)](https://user-images.githubusercontent.com/115772516/198227831-7bee56f5-2d9a-4888-a140-6c884ce432ee.png)

# Latihan 4

# Flowchart Menghitung Luas & Keliling Lingkaran

![Screenshot (67)](https://user-images.githubusercontent.com/115772516/198229758-497f89c1-c987-4137-b860-5713a18baec0.png)

# Menghitung luas dan keliling lingkaran 

![Screenshot (71)](https://user-images.githubusercontent.com/115772516/198231526-d99288d9-46de-4321-a928-744532520fea.png)

# Hasil luas dan keliling lingkaran

![Screenshot (73)](https://user-images.githubusercontent.com/115772516/198232371-adb9360a-1048-4c11-a169-21c3a87fc253.png)


