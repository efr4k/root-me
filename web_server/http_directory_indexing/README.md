# Step 1
Identify other folder than `/` which might not have index file already

In the source you find `/admin`:
```html
<!-- include("admin/pass.html") -->
```

# Step 2
Look through `/admin`

# Solution
```sh
curl http://challenge01.root-me.org/web-serveur/ch4/admin/backup/admin.txt
```
