# spectrum

![HTML5](https://img.shields.io/badge/-HTML5-18191b?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-18191b?style=flat-square&logo=css3)
![CSS3](https://img.shields.io/badge/-SASS-18191b?style=flat-square&logo=sass)

Главная страница сайта агентства по продаже элитной недвижимости. Сраница сделана на HTML + CSS с использованием препроцессора SASS.



![spectrum-2](https://github.com/hyggebox/Spectrum/assets/80201470/fcb31746-dd73-4473-ad17-a6ca76e60944)

Для страницы применена адаптивная верстка для различных размеров экрана — контрольные точки (брейкпоинты): 1200px, 900px, 800px, 600px, 400px.




![spectrum-1](https://github.com/hyggebox/Spectrum/assets/80201470/e41a6b1c-a02d-43f6-b79c-14ffb226f115)




## Запуск и установка 

Чтобы открыть страницу на локальной машине, необходимо:
- скачать файлы из репозитория
- в терминате перейти в папку с проектом и запустить на локальном сервере, например с помощью утилиты livereload: `livereload .`


## Формирование css-файла

- установите зависимости с помощью команды `npm install`
  
- Стили прописаны в `.scss` файлах в папке `sass/`. `.css` файл компилируется командой `node-sass sass/main.scss css/style.css`.
Также (вместо этого) финальный сжатый `.css` файл можно сформировать с помощью команды `npm run build:css` в терминале. 

- Для отслеживания изменений в процессе разработки используется команда `npm run start`

## Цели проекта
Проект написан в образовательных целях

