# Front-End-M6-EP3
----
npm create vite@latest
cd m6-ep1
npm install typescript ts-loader webpack webpack-cli --save-dev
npm install react-router-dom
npm install axios
npm install crypto-js
npm i --save-dev @types/crypto-js
npm install use-debounce
npm install json-server
npm run server
npm run dev

npm install vite-plugin-pwa --save-dev

----
1. Se ajusta el archivo de manifiesto

2. Se ajusta el Service Worker

3. Perifericos
Se implementa la geolocalizacion en la pagina de inicio Home.tsx
npm install leaflet
npm install --save-dev @types/leaflet


4. Dashboard ocupa api webserver local y funciona offline 
   EquipoMedico ocupa api webserver externa y funciona offline 

5. Se obtienen informes satisfactorios de acuerdo a lo solicitado
Se construye y despliega la PWA
npm run build
npm install -g serve
serve -s dist