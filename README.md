# phpinfo

```
git clone https://github.com/sergiosanznieto/phpinfo-1
cd phpinfo-1
git checkout main
```
```
php -f src/index.php -S 0.0.0.0:8080
```
```
curl localhost:8080/src/index.php
```
Instrucciones para contruir imagen docker
```
git checkout santander
docker build --file Dockerfile --tag sergiosanz/phpinfo:santander .
```
