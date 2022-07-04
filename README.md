# pyCrypt
pyCrypt is a linux command line tool for encrypting and decrypting single files or whole directories recursively.

Installation:
1. Install Python3
2. Install PyCryptodome
```sh
pip install pycryptodome
```
3. Download the two files of this repository: encrypt & decrypt
4. Move these files to ur /bin directory to use them in ur shell
```sh
cd pyCrypt
sudo mv encrypt /bin/encrypt
sudo mv decrypt /bin/decrypt
cd ..
rm -rf pyCrypt
```
-> encrypt and decrypt are now shell commands
```sh
encrypt -h 
decrypt -h 
```
-> shows help page

What does it do?
1. It en-/decrypts single files or all files in a directory of ur choice.
2. Optional u can let it encrypt the filenames too.
3. It can used in the terminal of ur linux computer.
4. -h / --help shows what u can do and how it works. 

Disclaimer: 
1. The developer is not liable for any damage. 
2. Dont run the script with root privileges. 

