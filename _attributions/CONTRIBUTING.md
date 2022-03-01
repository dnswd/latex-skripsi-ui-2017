# Panduan Kontribusi

Terima kasih atas minat rekan-rekan untuk mengusulkan atau membuat templat LaTeX
ini semakin baik, terutama ketika ada perubahan yang diperlukan atau ada
pembaharuan aturan dari pihak Rektorat Universitas Indonesia terkait format
tugas akhir. Setiap orang dapat dengan bebas membuat _fork_ repositori ini.
Setiap orang juga bebas mengajukan perubahan dengan mengubah templat ini pada
repositori hasil _fork_ masing-masing, kemudian melakukan _merge request_ (MR)
ke [repositori _upstream_ ini](https://gitlab.com/ichlaffterlalu/latex-skripsi-ui-2017).

Ketika membuat MR, pastikan _branch_ tujuan MR adalah _branch_ utama di
repositori _upstream_ yaitu _branch_ `master`. Pastikan juga perubahan yang
dilakukan tidak mengandung apapun dari konten tugas akhir sesungguhnya untuk
menghindari isu yang tidak diperlukan.

Untuk menjamin asal-muasal kontribusi tercatat dengan rapi, jangan lupa untuk
menambahkan nama Anda di sub-bagian [_Contributing_ pada dokumen README](./README.md#contributing).
Saat ini kami menggunakan _tools_ CLI [`all-contributors`](https://github.com/all-contributors/cli)
untuk memperbaharui daftar kontributor. Jika sudah memasang `all-contributors`,
maka panggil empat perintah berikut melalui _shell_ favorit Anda agar nama Anda
tercatat ke dalam daftar kontributor:

```shell
all-contributors add <username GitLab Anda> <tipe kontribusi Anda>
all-contributors generate
git add README.md
git commit
```

> Catatan: Jika merasa terlalu repot untuk memanggil `all-contributors`, maka
> pihak _maintainer_ repositori bisa memperbaharui daftar kontributor untuk Anda
> setelah MR diterima.

Jika tidak ada respon dari kami pada MR tersebut, silakan kirimkan surel ke
_maintainer_ repositori _upstream_ ini, yaitu `ichlasul.affan [at] ui.ac.id`,
dan beritahukan URL ke MR buatan Anda.
