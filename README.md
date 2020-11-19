
#examples

#Apache - Volume Beispiel
```sh
mkdir myhtml
cd myhtml
touch index.html
vi index.html
#inhalt in die Datei Schreiben (i, für Insert Modus)
#vi schließen mit :wq!
run -v "$PWD":/usr/local/apache2/htdocs/ -d -p 89:80 httpd
```

#Cheat-Sheets
* Docker https://www.docker.com/sites/default/files/d8/2019-09/docker-cheat-sheet.pdf
* VI: http://www.atmos.albany.edu/daes/atmclasses/atm350/vi_cheat_sheet.pdf
