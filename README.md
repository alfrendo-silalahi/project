# Pengenalan JavaScript (JS)

## Apa itu JavaScript?
JavaScript adalah bahasa pemrograman **high-level**, **dinamis**, dan **interpreted** yang digunakan untuk membuat:
- Interaktivitas di website (front-end)
- Aplikasi web/mobile (dengan framework seperti React, Vue)
- Back-end (Node.js)
- Game, IoT, dan lainnya.

## Fitur Utama
- ✔ **Multi-paradigma**: OOP, functional, procedural
- ✔ **Event-driven**: Menangani event seperti klik mouse
- ✔ **Asynchronous**: `Promise`, `async/await`
- ✔ **Dinamis**: Tipe data fleksibel

## Contoh Kode
```javascript
// Variabel
const nama = "Alice";
let usia = 25;

// Fungsi
function sapa() {
  console.log(`Halo, ${nama}!`);
}

// Arrow function
const tambah = (a, b) => a + b;

// Class (OOP)
class User {
  constructor(nama) {
    this.nama = nama;
  }
}
