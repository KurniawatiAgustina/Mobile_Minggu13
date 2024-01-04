
<a name="readme-top"></a>

<br />
<div align="center">
  <h3 align="center">PEMROGRAMAN MOBILE</h3>
  <br><br>
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="img/logo_readme.png" alt="Logo" width="80" height="80">
  </a>
  <br><br>
  <h3 align="center">Kurniawati Agustina</h3>
  <h3 align="center">3A - D4TI</h3>
</div>

<br>

<h1 align="center">PRAKTIKUM </h1>

<br>

<!-- ABOUT THE PROJECT -->
## Soal 1
```
import 'dart:async';
import 'package:flutter/material.dart';
import 'package:http/http.dart';
import 'package:http/http.dart' as http;

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Future demo Hatta', #menambahkan nama pada title
      theme: ThemeData(
          primarySwatch: Colors.blue,
          visualDensity: VisualDensity.adaptivePlatformDensity),
      home: const FuturePage(),
    );
  }
}

class FuturePage extends StatefulWidget {
  const FuturePage({Key? key}) : super(key: key);

  @override
  State<FuturePage> createState() => _FuturePageState();
}

class _FuturePageState extends State<FuturePage> {

  String result = '';
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('Back from Future Demo'),
      ),
      body: Center(
        child: Column(children: [
          const Spacer(),
          ElevatedButton(
            child: const Text('GO!'),
            onPressed: () {},
          ),
          const Spacer(),
          Text(result),
          const Spacer(),
          const CircularProgressIndicator(),
          const Spacer(),
        ]),
      ),
    );
  }
}
```

## Soal 2

Carilah judul buku favorit Anda di Google Books, lalu ganti ID buku pada variabel path di kode tersebut
![image](https://github.com/KurniawatiAgustina/Mobile_Minggu13/assets/113650883/f0c9c076-9de0-43fe-867e-8134d43174cc)
Kemudian cobalah akses di browser URI tersebut dengan lengkap seperti ini. Jika menampilkan data JSON, maka Anda telah berhasil.
![image](https://github.com/KurniawatiAgustina/Mobile_Minggu13/assets/113650883/3412a815-2f1d-434a-925e-558f480e8d9b)
![image](https://github.com/KurniawatiAgustina/Mobile_Minggu13/assets/113650883/cdd59146-8233-40df-81f6-d458562d2d0d)

## Praktikum 2: Menggunakan await/async untuk menghindari callbacks
![image](https://github.com/KurniawatiAgustina/Mobile_Minggu13/assets/113650883/1b460856-a403-4154-bbe6-975fda6df985)

Capture hasil praktikum Anda berupa GIF dan lampirkan di README. Lalu lakukan commit dengan pesan "W12: Soal 4".

## Praktikum 3: Menggunakan Completer di Future

![image](https://github.com/KurniawatiAgustina/Mobile_Minggu13/assets/113650883/1991f761-099b-4963-9974-fb1627f90f24)

Capture hasil praktikum Anda berupa GIF dan lampirkan di README. Lalu lakukan commit dengan pesan "W12: Soal 6




