## Использывание grunt

Соберите проект с использыванием grunt, все файлы и папки должны создаваться только с помощью grunt, структура собранного проекта:

```
├── public         # the place for production version
│----| index.html  # main file
│----| img         # dir with images
│----| app.css     # main css file
│----| app.min.js  # main js min file
└──
```

Создайте в файле package.json для описания вашего проекта

Также сделайте watcher который бует следить за изменениями в вашем проекте и компилировать новый css js и если нужно картинки
