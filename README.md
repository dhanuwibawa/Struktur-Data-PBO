Perbedaan antara ARRAY dengan COLLECTION

ARRAY 
- Bersifat statis, ukurannya tetap (meskipun bisa ditambah elemen, struktur dasarnya tidak sefleksibel Collection).
- Menyimpan data dalam bentuk key-value (kunci dan nilai).
- Tidak memiliki method bawaan yang kompleks seperti filtering, mapping, atau sorting otomatis.
- Akses data dilakukan dengan operator indeks ($array[0] atau $array['key']).
- Tidak termasuk objek, melainkan tipe data bawaan PHP.

COLLECTION
- Bersifat dinamis dan lebih fleksibel dalam pengelolaan data.
- Dibangun di atas class Illuminate\Support\Collection (objek dari Laravel).
- Memiliki banyak method siap pakai seperti map(), filter(), pluck(), sum(), avg(), dll.
- Dapat dikombinasikan, disaring, diurutkan, dan dimanipulasi dengan mudah tanpa looping manual.
- Lebih cocok untuk pengolahan data kompleks dalam framework Laravel.