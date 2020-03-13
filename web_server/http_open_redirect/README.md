# Step 1
Identify redirect urls and their requirements

http://challenge01.root-me.org/web-serveur/ch52/?url=https://facebook.com&h=a023cfbf5f1c39bdf8407f28b60cd134

You can see the `h` parameter is the MD5 of the `url` parameter

# Step 2
Calculate MD5 of random url (`url=http://minip.no`)
```sh
echo -n http://minip.no | md5sum
```

# Answer
http://challenge01.root-me.org/web-serveur/ch52/?url=http://minip.no&h=64f1804b47f82d900d54d93bf73b8dbb
