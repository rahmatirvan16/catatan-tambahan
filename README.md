### Javascript Dasar
* Javascript-Dasar/while.js
  ```
  var nilaiAwal = 1;

  while (nilaiAwal <= 10) {
  console.log('Hello World ' + nilaiAwal);
  nilaiAwal++;
  }
  ```
  <img width="905" height="336" alt="image" src="https://github.com/user-attachments/assets/7af12bc1-ce6b-46fa-9a32-b756208f5709" />


* Javascript-Dasar/for.js
  ```
  for (var nilaiAwal = 0; nilaiAwal <= 10; nilaiAwal++) {
    console.log('Hello World ke-' + nilaiAwal);
  }
  ```
  <img width="876" height="347" alt="image" src="https://github.com/user-attachments/assets/460bd159-676f-44a0-bcdf-071ae806ca47" />

* Javascript-Dasar/angkot2.js
  <br>latihan penggabungan while dan for
  ```
  var jmlAngkot = 10;
  var angkotBeroperasi = 6;
  var noAngkot = 1;
  
  while (noAngkot <= angkotBeroperasi) {
      console.log('Angkot No.' + noAngkot + ' beroperasi dengan baik.');
      noAngkot++;
  }
  
  for (var noAngkot = angkotBeroperasi + 1; noAngkot <= jmlAngkot; noAngkot++) {
      console.log('Angkot No.' + noAngkot + ' sedang tidak beroperasi');
  }
  ```
  <img width="911" height="338" alt="image" src="https://github.com/user-attachments/assets/24e81d7d-2384-4ad8-af1e-c546f4e22931" />

* Javascript-Dasar/angkot3.js
  <br> penggunaan if didalam for
  ```
  var jmlAngkot = 10;
  var angkotBeroperasi = 6;
  var noAngkot = 1;

  for (var noAngkot; noAngkot <= jmlAngkot; noAngkot++) {
  if (noAngkot <= angkotBeroperasi) {
  console.log('Angkot No. ' + noAngkot + ' beroperasi dengan baik.');
  } else {
  console.log('Angkot No. ' + noAngkot + ' sedang tidak beroperasi.');
  }
  }
  ```
  <img width="907" height="332" alt="image" src="https://github.com/user-attachments/assets/7eb7613e-8ed1-42af-b1ed-824036f118ab" />

* Javascript-Dasar/angkot4.js
  <br> penggunaan if else if didalam for
  ```
  var jmlAngkot = 10;
  var angkotBeroperasi = 6;
  var noAngkot = 1;
  var angkotLembur = 8;
  
  for (var noAngkot; noAngkot <= jmlAngkot; noAngkot++) {
    if (noAngkot <= angkotBeroperasi) {
        console.log('Angkot No. ' + noAngkot + ' beroperasi dengan baik.');
    } else if (noAngkot === angkotLembur) {
        console.log('Angkot No. ' + noAngkot + ' sedang lembur.');
    } else {
        console.log('Angkot No. ' + noAngkot + ' sedang tidak beroperasi.');
    }
  }
  ```
  <img width="906" height="341" alt="image" src="https://github.com/user-attachments/assets/6fea4a5f-c57c-430a-889f-643dd5ab3357" />

* Javascript-Dasar/angkot5.js
  <br> penggunaan if else if OR didalam for
  ```
  var jmlAngkot = 10;
  var angkotBeroperasi = 6;
  var noAngkot = 1;
  var angkotLembur = 8;
  
  for (var noAngkot; noAngkot <= jmlAngkot; noAngkot++) {
      if (noAngkot <= angkotBeroperasi) {
          console.log('Angkot No. ' + noAngkot + ' beroperasi dengan baik.');
      } else if (noAngkot === angkotLembur || noAngkot === 10) {
          console.log('Angkot No. ' + noAngkot + ' sedang lembur.');
      } else {
          console.log('Angkot No. ' + noAngkot + ' sedang tidak beroperasi.');
      }
  }
  ```
  <img width="904" height="342" alt="image" src="https://github.com/user-attachments/assets/b9132cb1-c095-489f-ad9c-68b61e25d62a" />

* Javascript-Dasar/angkot6.js
  <br> penggunaan if else if AND OR didalam for
  ```
  var jmlAngkot = 10;
  var angkotBeroperasi = 6;
  var noAngkot = 1;
  var angkotLembur = 8;
  
  for (var noAngkot; noAngkot <= jmlAngkot; noAngkot++) {
      if (noAngkot <= angkotBeroperasi && noAngkot !== 4) {
          console.log('Angkot No. ' + noAngkot + ' beroperasi dengan baik.');
      } else if (noAngkot === angkotLembur || noAngkot === 10 || noAngkot === 4) {
          console.log('Angkot No. ' + noAngkot + ' sedang lembur.');
      } else {
          console.log('Angkot No. ' + noAngkot + ' sedang tidak beroperasi.');
      }
  }
  ```
  <img width="908" height="344" alt="image" src="https://github.com/user-attachments/assets/6fd2af6c-6401-4c4d-8ada-88f5c55c86eb" />

* Javascript-Dasar/switch.js
  <br> penggunaan switch
  ```
  var item = prompt('masukkan nama makanan/minuman: \n (cth: nasi, daging, susu, soda, hamburger, kentang)');
  switch (item) {
    case 'nasi':
    case 'daging':
    case 'susu':
        alert('makanan/minuman SEHAT');
        break;
    case 'hamburger':
    case 'softdrink':
        alert('makanan/minuman TIDAK SEHAT');
        break;
    default:
        alert('anda memasukkan makanan/minuman yang salah');
        break;
  }
  ```
  <img width="681" height="221" alt="image" src="https://github.com/user-attachments/assets/3d5939fb-8830-464b-bcfe-590bc65e0c1d" />

  
### Javascript Lanjutan
### PHP Dasar
### PHP Object
### PHP MVC
### Ngobar Seri 9-11
