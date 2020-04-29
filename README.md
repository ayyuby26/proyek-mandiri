### Bug yang terselesaikan :

- Tidak bisanya menggunakan Action Bar Activity karena changes for Android Support Library, revision 22.1.0 (April 2015) maka jadinya menggunakan AppCompatActivity, read more http://developer.android.com/tools/support-library/index.html

- Coding dari modul ListAdapterHandphone.java ada yang kurang, kurangnya yaitu textNama.setText(hp.getNama());

- karena saya mendebug apk ini dengan os Pie/ api 28 maka ada baris perintah yang perlu ditambahkan di AndroidManifest.xml didalam </application> yaitu <uses-library android:name="org.apache.http.legacy" android:required="false" />, read more https://developer.android.com/about/versions/pie/android-9.0-changes-28?hl=id



Fungsi2 module :
MainActivity.java = menampilkan daftar hp

![alt text](https://i.ibb.co/VHGT11n/image.png)


- FormHandphone.java = untuk merubah daftar hp
- DetailHandphone.java = untuk informasi detail hp
- AsyncInvokeURLTask.java = mengambil json data hp
- Handphone.java = tempat informasi hp di simpan di class Handphone
