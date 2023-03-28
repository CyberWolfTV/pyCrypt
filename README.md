# pyCrypt
pyCrypt is a linux command line tool for encrypting and decrypting single files or whole directories file by file.

Installation:
1. Install Python3 & git
2. Install PyCryptodome
```sh
pip install pycryptodome
```
3. Download the two files of this repository: encrypt & decrypt
```sh
git clone https://github.com/CyberWolfTV/pyCrypt.git
```
4. Move these files to ur /bin directory to use them in ur shell
```sh
cd pyCrypt
chmod +x encrypt
chmod +x decrypt
sudo mv encrypt /bin/encrypt
sudo mv decrypt /bin/decrypt
cd ..
rm -rf pyCrypt
```
-> encrypt and decrypt are now commands
```sh
encrypt -h 
decrypt -h 
```
-> shows help page

***
What does it do?
1. It encrypts and decrypts single files or all files in a directory of ur choice.
2. Optional u can let it encrypt the filenames and/or the directory names too.
3. It can be used in the terminal of ur linux computer.
4. -h / --help shows what u can do and how it works.

***
If ur using the old version (in master branch till 29.03.2023):
1. Download the old version -> branch "Version_2"
2. Decrypt all ur files
3. Install the new version and encrypt ur files again.
4. Now u can just keep using the new version.

***
If ur using the old version (in master branch till 11.11.2022):
1. Download the old version -> branch "Version_1"
2. Decrypt all ur files
3. Install the new version and encrypt ur files again.
4. Now u can just keep using the new version.
