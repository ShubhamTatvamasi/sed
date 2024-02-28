# sed

update IP
```bash
sed -i 's/10.0.0.22/172.16.4.117/' /tmp/myfile
```

Add `''` for running `sed` command on macOS:
```bash
sed -i '' 's/10.0.0.22/172.16.4.117/' /tmp/myfile
```


Replace space with new line:
```bash
sed 's/ /\n/g' id_rsa
```
