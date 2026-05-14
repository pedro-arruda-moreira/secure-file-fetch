# safe-file-fetch
Access control on public buckets!

### Why?
Suppose you have a file 🗃️ that you need to be (even more) secure, like a AES encrypted 🔐 ZIP file. It's already encrypted, but you want to keep it from curious eyes 👀, while maintaining it easy for you (and only you!) to download.

### Ok, but how?
1) download this repo
2) execute serve.sh
3) type your first name, year of birth and password
4) check generated key
5) create a new folder named as the key
6) put metadata.json inside it
```json
{
    "name": "file.txt"
}
```
7) put your file on the same folder named as `file`
8) now just replicate it inside a bucket on AWS/GCP/whatever...
9) enjoy!

### Is there a demo?
Sure, just check [here](https://insert_link)!
```
first name: test
year of birth: 1000
password: p4ssword
```