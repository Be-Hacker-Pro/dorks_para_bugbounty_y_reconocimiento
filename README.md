# Listado de dorks para el proceso de reconocimiento y utiles en procesos de bug bounty


## Listado de directorios 
* site:dominio.com intitle:index.of

## archivo de configuración 
* site:dominio.com ext:xml | ext:conf | ext:cnf | ext:reg | ext:inf | ext:rdp 

## archivos de bases de datos
* site:dominio.com ext:sql | ext:dbf | ext:mdb

## portales de wordpress 
* site:dominio.com inurl:wp- | inurl:wp-content | inurl:plugins | inurl:uploads | inurl:themes | inurl:download

## archivos de log
* site:dominio.com ext:log

## archivos de backup y antiguos
* site:dominio.com ext:bkf | ext:bkp | ext:bak | ext:old | ext:backup

## paginas de login
* site:dominio.com inurl:login | inurl:signin | intitle:Login | intitle: signin | inurl:auth

## errores de sql 
* site:dominio.com intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()"

## archivos de configuracion de apache
* site:dominio.com filetype:config "apache"

## archivo de robots.txt
* dominio.com/robots.txt

## busqueda en domaineye
* https://domaineye.com/similar/dominio.com

## documentos publicamente expuestos
* site:dominio.com ext:doc | ext:docx | ext:odt | ext:pdf | ext:rtf | ext:sxw | ext:psw | ext:ppt | ext:pptx | ext:pps | ext:csv

## archivo de phpinfo:
* site:dominio.com ext:php intitle:phpinfo "published by the PHP Group"

## posibles backdoors
* site:dominio.com  inurl:shell | inurl:backdoor | inurl:wso | inurl:cmd | shadow | passwd | boot.ini | inurl:backdoor

## archivos de instalacion y setup
* site:dominio.com  inurl:readme | inurl:license | inurl:install | inurl:setup | inurl:config

## open redirects:
* site:dominio.com inurl:redir | inurl:url | inurl:redirect | inurl:return | inurl:src=http | inurl:r=http

## apache strusts RCE
* site:dominio.com ext:action | ext:struts | ext:do

## exposicion en portales de terceros
* site:http://ideone.com | site:http://codebeautify.org | site:http://codeshare.io | site:http://codepen.io | site:http://repl.it | site:http://justpaste.it | site:http://pastebin.com | site:http://jsfiddle.net | site:http://trello.com | site:*.atlassian.net | site:bitbucket.org "dominio.com"

## indexado en entradas de pastebin
* site:pastebin.com dominio.com

## empleados en linkedin
* site:linkedin.com employees dominio.com

## archivos sensibles en .htaccess
* site:dominio.com inurl:"/phpinfo.php" | inurl:".htaccess"

## Encontrar subdominios 
* site:*.dominio.com

## busqueda en atlassian y bitbucket
* site:atlassian.net | site:bitbucket.org "dominio.com"
 
## busqueda en stackoverflow 
* site:stackoverflow.com "dominio.com"
 
## busqueda en github
* https://github.com/search?q=%22*.dominio.com%22
 
## busqueda en digitaloceanspaces
* site:digitaloceanspaces.com "dominio.com"

## busqueda en shodan
* https://www.shodan.io/search?query=dominio.com

## busqueda en censys
* https://search.censys.io/domain?q=dominio.com

## busqueda por certificados de transparencia
* https://crt.sh/?q=dominio.com
