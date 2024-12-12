# nexus
Tutor Nexus Vps

sudo apt update && sudo apt upgrade -y

sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y

sudo curl https://sh.rustup.rs -sSf | sh

source $HOME/.cargo/env

export PATH="$HOME/.cargo/bin:$PATH"

rustup update

sudo apt install -y protobuf-compiler

sudo apt install screen 

screen -S nexus

sudo curl https://cli.nexus.xyz/install.sh | sh

cara ambil prover-id klik di bagian mana aja di web beta nexus nya masuk ke bagian impeksi ke aplikasi penyimpanan lokal di situ ada flutter.proverid nah itu id nya


Kalau misal ada elor pas runing masalah prover id CTRL+C aja dulu lanjut ke

cd .nexus/

nano prover-id

Nah di situ prover id yang tadi di ambil masukin di situ jangan lupa delete prover-id bawaan yg di vps baru paste lanjut 

CTRL+X CTRL+Y enter

Lanjut 

cd $home

runing lagi

sudo curl https://cli.nexus.xyz/install.sh | sh

Cara keluar dari screen CTRL+A+D

Cek Screen

screen -r nexus


Oh iya lupa kalau ntar ada pilihan 1 2 3 pilih aja 1 terus enter pas runing pertama
