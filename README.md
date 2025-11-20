# soal_interview
Soal Interview IT

# soal_interview
Soal Interview IT

---

## 1. Pertukaran Nilai Variabel

Lengkapi fungsi `tukarNilai()` untuk menukar nilai yang tersimpan dalam variabel `x` dan `y` sehingga nilai akhir `x` sama dengan nilai awal `y` dan sebaliknya.

```javascript
function tukarNilai() {
  let x = 19;
  let y = 84;
  console.log('Nilai Awal: x =', x, ', y =', y); 		
  // Mulai Disini (Tukar Nilai x dan y)

  // End Tukar Nilai Disini
  console.log('Nilai Akhir: x =', x, ', y =', y);
}
tukarNilai();
````

## 2. Klasifikasi Angka Ganjil/Genap

Lengkapi fungsi `klasifikasiAngka(data)` untuk mengembalikan sebuah *array* baru yang berisi status "Ganjil" atau "Genap" untuk setiap elemen dalam `deretAngka`.

**Ketentuan Wajib:**
1.  Gunakan method **`.map()`** dalam implementasi Anda.
2.  Gunakan **operator ternary (`? :`)** dalam implementasi Anda.

```javascript
// Output yang diharapkan: [ 'Ganjil', 'Genap', 'Ganjil', 'Genap', 'Ganjil' ]

const deretAngka = [1, 2, 3, 4, 5];
function klasifikasiAngka(data) {

}
console.log('Input = ', deretAngka)
console.log('Output = ', klasifikasiAngka(deretAngka))
```


## 3. Analisis dan Pemisahan Angka (Ganjil dan Genap)

Lengkapi fungsi `analisisGanjilGenap(dataAngka)` yang menerima sebuah array angka. Fungsi harus mengembalikan sebuah objek yang berisi:
1.  *Array* angka ganjil (**`ganjil`**)
2.  *Array* angka genap (**`genap`**)
3.  Total hitungan angka ganjil (**`jumlahGanjil`**)
4.  Total hitungan angka genap (**`jumlahGenap`**)

**Ketentuan Wajib:** Gunakan method **`.filter()`** untuk memisahkan angka ganjil dan genap.

```javascript
const data = [1, 22, 5, 8, 11, 14, 7, 30, 9];
function analisisGanjilGenap(dataAngka) {
  const genap = 
  const ganjil = 
  return {
    ganjil: 
    genap: 
    jumlahGanjil:
    jumlahGenap: 
  };
}
console.log(analisisGanjilGenap(data));
```

## 4. Menggabungkan Data Objek

Lengkapi fungsi `gabungData(profile, status)` untuk membuat dan mengembalikan sebuah objek baru bernama `detailLengkap`.

**Tujuan:** Objek ini harus berisi semua properti dari `profile`, semua properti dari `status`, dan properti **`tanggalGabung`**.

```javascript
const profile = { 
  nama: "Rina", 
  departemen: "IT", 
  usia: 25
};
const status = { 
  isAktif: true, 
  gaji: 5000000
};
function gabungData(profile, status) {
  const detailLengkap = {
    tanggalGabung: '2024-01-15',
  }
  return detailLengkap;
}

console.log(gabungData(profile, status));
```

## 5. Pemanggilan API Asinkronus

Buat fungsi asinkronus **`ambilUsername()`** yang mengambil data pengguna dengan ID 1 dari *endpoint* `https://jsonplaceholder.typicode.com/users/`, kemudian cetak *username* pengguna tersebut ke konsol.

**Ketentuan Wajib:**
1.  Fungsi harus didefinisikan dengan kata kunci **`async`**.
2.  Gunakan **`await`** bersama dengan fungsi bawaan **`fetch()`** untuk menangani panggilan API.
3.  Sertakan mekanisme **penanganan *error***.

```javascript
async function ambilUsername() {

}
ambilUsername();
```



