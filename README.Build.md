Build instructions for the impatient


```bash
curl https://raw.githubusercontent.com/centreon-deb/php-mdb2/debian/bootstrap | sh
cd php-mdb2 && git deb-pkg -C -U -u 2.5.0b5 -d origin/debian build
```

Further instruction in the [README.Build.md](README.Build.md) file.
