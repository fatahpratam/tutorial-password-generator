# Chapter 8: Membuat aplikasi password generator

## GitHube Pages
Link: [Password Generator](https://fatahpratam.github.io/tutorial-password-generator/)

## Youtube Tutorial
- Link: [Full Stack React Developer Course with Appwrite](https://www.youtube.com/watch?v=Bvwq_S0n2pk)
- Creator: [HiteshCodeLab](https://www.youtube.com/@HiteshCodeLab)

## Cara kerja aplikasi
- Terdapat sebuah input-box untuk menampilkan password yang telah di generate dan di sampingnya terdapat sebuah tombol [Copy] untuk menyalin passwordnya.
- Di bawahnya ada slider untuk menentukan panjang karakter password yang diinginkan.
- Di samping slider, ada checkmark [Numbers] untuk membolehkan bilangan di dalam password.
- Di sampingnya lagi, juga ada  checkmark [Characters] untuk membolehkan karakter khusus di dalam password.
- Setiap slider digeser, checkmark [Numbers] di klik, checkmark [Characters] di klik, atau website di-reload, password baru akan di-generate.

## Tips
- Untuk memastikan agar state selalu responsive (update UI konsisten), gunakan callback sebagai argument ketika memanggil method `useState()`.


## Fungsi react
- `useCallback()` -> useCallback adalah sebuah React Hook yang memungkinkan Anda untuk melakukan cache pada sebuah definisi fungsi di antara render ulang.
- `useEffect()` -> useEffect adalah sebuah React Hook yang memungkinkan Anda untuk menyinkronkan sebuah komponen dengan sistem eksternal.
- `useRef()` -> useRef adalah sebuah React Hook yang memungkinkan Anda mereferensikan sebuah nilai yang tidak diperlukan untuk rendering.