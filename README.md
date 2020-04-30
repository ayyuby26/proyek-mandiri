##### Bug yang terselesaikan :

- Tidak bisanya menggunakan Action Bar Activity karena changes for Android Support Library, revision 22.1.0 (April 2015) maka jadinya menggunakan AppCompatActivity, read more http://developer.android.com/tools/support-library/index.html

- Coding dari modul ListAdapterHandphone.java ada yang kurang, kurangnya yaitu ```textNama.setText(hp.getNama());```

- karena saya mendebug apk ini dengan os Pie/ api 28 maka ada baris perintah yang perlu ditambahkan di AndroidManifest.xml didalam ```</application>``` yaitu ```<uses-library android:name="org.apache.http.legacy" android:required="false" />```, read more https://developer.android.com/about/versions/pie/android-9.0-changes-28?hl=id



##### berikut screenshot2 dari aplikasi :
tampilan utama

![image](https://user-images.githubusercontent.com/18584572/80631525-0dc9d700-8a80-11ea-98c6-1246efd2bdd5.png)


Tampilan ubah produk

![image](https://user-images.githubusercontent.com/18584572/80630636-ba0abe00-8a7e-11ea-881b-037943751b61.png)


Tampilan detail

![image](https://user-images.githubusercontent.com/18584572/80630291-305af080-8a7e-11ea-8c8b-976a0eff644b.png)

Tampilan pencarian 

![image](https://user-images.githubusercontent.com/18584572/80631132-7ebcbf00-8a7f-11ea-827b-6a57c0f5a37f.png)

Tampilan tambah produk

![image](https://user-images.githubusercontent.com/18584572/80631184-9005cb80-8a7f-11ea-90e5-e81c6ac6b6e2.png)

Tampilan hapus produk

![image](https://user-images.githubusercontent.com/18584572/80631247-aa3fa980-8a7f-11ea-9e10-efa8bcdc77fc.png)
