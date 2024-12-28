# uploader
Telegram uploader bot in cloudflare

add 2 kv in storage and database 
```
1 for Files named uploadedFiles
1 for Sessions named SESSIONS
```
create new worker and put the code in it
in settings add 2 KV binding
```
1 name SESSIONS
1 nae UPLOADS
```
open your link 
login

then 

/init 

```
/   to upload file
/list to see uploaded files
```
