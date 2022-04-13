Install npm install jwt-decode
https://stackoverflow.com/questions/48075688/how-to-decode-the-jwt-encoded-token-payload-on-client-side-in-angular


swaggerhub; change 2.0 to 3.0.1


passwort uek294
install certificate => rechtsklick =>> Zertifikat installieren => weiter => Trusted Root Ceticateion Authorities=> erlauben fertig
https://www.codejava.net/frameworks/spring-boot/configure-https-with-self-signed-certificate

ng serve --ssl --ssl-cert C:\\devsbb\\angular\\todo-web\\src\\ssl\\localhost.crt --ssl-key C:\\devsbb\\angular\\todo-web\\src\\ssl\\localhost.key

angular.json ändern
"serve": {
          "builder": "@angular-devkit/build-angular:dev-server",
          "options": {
            "browserTarget": "todo-web:build",
            "sslCert": "src/ssl/localhost.crt",
            "sslKey" :"src/ssl/localhost.key",
            "ssl": true
          },
