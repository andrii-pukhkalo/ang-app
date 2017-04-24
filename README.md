# app

installing demo app

#required node version is 6.10.2 and npm 3.10.10

```bash
sudo npm i -g @angular/cli
ng new ang-app2
cd ang-app2/
npm i angular-in-memory-web-api
sudo rm -R src
mkdir src && git clone https://github.com/andrii-pukhkalo/app.git src/
ng serve
