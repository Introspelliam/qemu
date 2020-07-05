# qemu

## 环境准备

apps
```
sudo apt install -y iasl nasm


# install rustc
rustup update stable
cargo install cbindgen --force

# nasm
sudo apt-get remove nasm
hash -d nasm
wget http://www.nasm.us/pub/nasm/releasebuilds/2.14.02/nasm-2.14.02.tar.bz2
tar xfj nasm-2.14.02.tar.bz2
cd nasm-2.14.02/
./autogen.sh
./configure --prefix=/usr/local/ 
make 
sudo make install
hash -d nasm

```

requirements
```
PyCryptodomex
avocado-framework==65.0
docutils
sphinx>=2.0.0
sphinx-rtd-theme>=0.4.3
sphinxcontrib-plantuml>=0.15
```

修改CC CXX等
```

```
