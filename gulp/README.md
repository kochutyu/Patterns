# Сборка проекта на Gulp 4, Версия 1

## Описание проекта:
С помощью этих файлов вы сможете быстро настроить сборку вашего проекта на Gulp.

## Структура файлов и папок:  
>./src  
>>	/css  
>>>		/main.css  
>>>		/media.css  
>>	/js  
>>>		/lib.js  
>>>		/main.js  
>./gulpfile.js  
>./package.json  
>./index.html  

## Инструкция:  
1. Скачать все файлы в любую директорию   
2. Ввести в терминале/командной строке команду: npm i (должен быть установлен node.js) 
3. Выполнить команду: gulp dev (запуск таска dev, который очистит каталог build и запустит таск watch - отслеживает изменения в файлах html, css и js) 
4. Писать свой код и наслаждаться автоматической сборкой проекта. 

## Ссылки:
* __Репозиторий GitHub:__ https://github.com/morphIsmail/gulp_settings

## npm setup:
npm install del
npm install browser-sync gulp --save-dev
npm install gulp-cli -g
npm install gulp -D
npm install --save-dev gulp-autoprefixer
npm install gulp-clean-css --save-dev
npm install --save-dev gulp-concat
npm install --save-dev gulp-uglify
