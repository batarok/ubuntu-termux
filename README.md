# ubuntu-termux
Sebelum download file ubuntu.sh perlu melakukan hal ini di termux
pkg update -y && pkg upgrade -y
kemudian
pkg -y install wget proot

lalu download file ubuntu.sh dan lakukan install ubuntu.sh dengan cara
wget https://github.com/batarok/ubuntu-termux/blob/main/ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh

tunggu proses nya sampai selesai, jika sudah selesai untuk login ke ubuntu jalankan perintah ./start-ubuntu.sh
