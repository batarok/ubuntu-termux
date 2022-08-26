# ubuntu-termux
Sebelum download file ubuntu.sh perlu melakukan hal ini di termux \
pkg update -y && pkg upgrade -y

kemudian \
pkg -y install wget proot

lalu download file ubuntu.sh dan lakukan install ubuntu.sh dengan cara \
wget https://raw.githubusercontent.com/batarok/ubuntu-termux/main/ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh \
tunggu proses nya sampai selesai, jika sudah selesai untuk login ke ubuntu jalankan perintah ./start-ubuntu.sh

Jika ada error setelah menjalankan bash ubuntu.sh kemungkinan file image ubuntu nya sudah tidak ada, maka perlu diubah bagian \
https://partner-images.canonical.com/core/focal/current/ubuntu-focal-core-cloudimg \
dengan cara cek dahulu ke https://partner-images.canonical.com/core/ image apa yg masih tersedia <b>hirsute</b> \
brarti di ubah menjadi https://partner-images.canonical.com/core/hirsute/current/ubuntu-hirsute-core-cloudimg

seperti itu
