
//Meter en /run el archivo wordlist.lst y el hash a descifrar en hash.txt
./john --wordlist=wordlist.lst --rules=all --format=raw-sha1 hash.txt
