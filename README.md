# storybook_practicum

1.	Buat proyek flutter baru → storybook_practicum<br>
 ![image](https://github.com/user-attachments/assets/5c7f4872-482b-4deb-b4ae-c2e724679be9)

2.	Buka Code Editor kalian<br>
 ![image](https://github.com/user-attachments/assets/0759bfc5-b0d3-4bcb-8d55-6b7bd1e8575a)

3.	Di dalam lib buat folder pages di dalamnya terdapat 3 files:
a.	title_page.dart<br>
 ![image](https://github.com/user-attachments/assets/dca02569-e48b-4662-98e5-9c7e7ce8cd3e)

b.	scene_page.dart<br>
 ![image](https://github.com/user-attachments/assets/7da1c59d-4448-4ea6-935e-19b954ae949e)

c.	end_page.dart<br>
 ![image](https://github.com/user-attachments/assets/a7cd4759-5756-477c-85f6-071ef91dac42)


4.	Buka lib/main.dart dan ganti isinya dengan kode berikut untuk membuat struktur PageView:<br>
![image](https://github.com/user-attachments/assets/9a120478-b791-4fbb-b5a2-6cf28e226cf0)

5.	Untuk mencegah error, isi setiap file di folder pages dengan StatelessWidget boilerplate sederhana. Contoh untuk title_page.dart<br>
![image](https://github.com/user-attachments/assets/5db4c72d-306b-42a9-9a72-e6b5c1a970c6)
 
6.	Lakukan hal yang sama untuk scene_page.dart dan end_page.dart, cukup tampilkan teks judul halaman<br>
![image](https://github.com/user-attachments/assets/d1a6abb8-565e-441e-bfd0-1a0b557e5ab8)

7.	Fokus pada lib/pages/scene_page.dart → ganti isinya dengan kerangka StatefulWidget<br>
![image](https://github.com/user-attachments/assets/8064e681-1421-4edd-906a-606e5161f386)

8.	Tambahkan Astronaut & Balon Dialog (Double Tap). Di dalam Stack, tambahkan Positioned untuk astronaut<br>
![image](https://github.com/user-attachments/assets/fe76f40e-28ff-432a-bc36-db1ee3cfc0e3)

9.	Tambahkan Peti & Petunjuk (Long Press). Di dalam Stack, tambahkan Positioned untuk peti.<br>
![image](https://github.com/user-attachments/assets/d9d44f29-20d2-41be-8ff5-de726dc0496b)

10.	Tambahkan Kunci & Logika Drag-and-Drop. Di dalam Stack, tambahkan Positioned untuk kunci. Ini bagian paling kompleks<br>
![image](https://github.com/user-attachments/assets/d5b4ac91-f8cc-4bb5-9974-21fcdf009e3b)

11.	Hot Reload & Uji Coba: Coba semua interaksi: double tap astronaut, long press peti, dan geser kunci ke peti.<br>
![image](https://github.com/user-attachments/assets/8057376a-f592-4b73-acbe-bda1489391c1)

12.	Efek Visual (InkWell) → Buka lib/pages/title_page.dart
13.	Bungkus ElevatedButton dengan Card dan InkWell untuk efek yang lebih bagus. Ganti ElevatedButton dengan kode berikut:<br>
![image](https://github.com/user-attachments/assets/2aa418c0-e5c6-4838-8138-85af7be03498)

14.	Kita akan membuat latar belakang bisa digeser sedikit secara horizontal atau vertikal (seperti melihat lewat teleskop), tapi tidak keduanya sekaligus.
15.	Kembali ke lib/pages/scene_page.dart
16.	Kita modifikasi Container latar belakang. Pertama, tambahkan Offset untuk posisi background di State<br>
![image](https://github.com/user-attachments/assets/ab27b0f6-16b8-49e9-abd3-08d6c0f34ab5)

17.	Bungkus Container latar belakang dengan RawGestureDetector dan Transform<br>
![image](https://github.com/user-attachments/assets/8e1bbba9-7d04-445e-8bf2-583735f43c08)

18.	Ujicoba: Coba geser latar belakang. Kalian hanya bisa menggesernya di satu sumbu (horizontal atau vertikal) dalam satu waktu.
19.	Fungsionalitas Zoom dengan InteractiveViewer
20.	Di lib/pages/scene_page.dart, bungkus seluruh Stack dengan widget InteractiveViewer<br>
![image](https://github.com/user-attachments/assets/2e554926-df24-41ba-b711-988a321ef681)

21.	Hot Reload dan seluruh adegan interaktif bisa di-zoom dan di-pan dengan mudah.<br>
![image](https://github.com/user-attachments/assets/bb2a60e8-c933-4548-81a8-706a24561fa4)
