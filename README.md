# Infected WordPress Analytics

Find filename match in X days

```shell
find /home/admin/web/inheridas.cl/public_html/wp-content/uploads/ -iname "*.php" -atime -30 -type f -ls
```
Remove files with exceptions

```shell
shopt -s extglob

rm -v !("filename1"|"filename2") 
```
