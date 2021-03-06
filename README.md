﻿# Индивидуальный проект - практика pug и less

## Запуск сборки проекта
В адресе вашего проекта на ПК не должно быть кириллицы. Идеально — создайте с корне диска С: или D: папку "projects" и разместите в нее папку вашего проекта. У вас может получится что то похожее на это: C:\projects\Ind-pug-less-task-project

----

**Важно.** Имя вашего проекта должно выглядеть как "WD05-project-1-Фамилия", например "WD05-project-1-Popov".

----

1. Клонирование проекта к себе на ПК               
```sh
git clone github.com/nobleworkshop/Ind-pug-less-task-project.git
```

2. Переходим в созданную папку
```sh
cd Ind-pug-less-task-project
```

3. Устанавливаем все зависимости
```sh
npm install
```

4. Запускаем сборку
```sh
gulp
```


### code guide

Соглашение по написанию кода. Общие правила которых будут придерживаться все члены команды:

* [less] - CSS препроцессор (По личному усмотрению можете заменить на SCSS)
* [Flexbox] - Для построения структуры страниц используем флексы
* [Bootstrap grid 4] - В сборке уже есть сетка от bootstrap-4
* [Табы] - Проверьте, что бы настройки отступов в редакторе были сделаны табами (это важно для PUG файлов)
* [Bem] - При написании кода используем BEM naming (Блок, Элемент, Модификатор)