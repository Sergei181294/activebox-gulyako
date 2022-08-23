# Как сделать сборку через Parcel
1) npm init   - иницилизируем наш проект, создаться файл package.json
2) npm install --save-dev parcel - установим наш сборщик.
3) npm install --save-dev sass - установим sass
4) npm install --save-dev @parcel/transformer-sass - установим "переводчик" из sass в css
5) в package.json добавить скрипты start и build - для запуска и сборки
   "scripts": {
     "start": "parcel",
     "build": "parcel build"
     },
6) Создаем архитектуру нашего проекта: папка src, в ней файл index.html, папка с файлами sass в ней документ style.scss
7) style.scss - файл в котором будут подключаться все стили для блоков и этот файл будет подключаться в html:
  "<link rel="stylesheet" href="sass/style.scss">"
8) npm run start - запускаем сборку нашего проекта (У нас создалась папка dist в которой три файла html, css, js)
9) Когда у нас запущен старт, то все изменения обновляются автоматически.# activebox-gulyako
# activebox-gulyako
