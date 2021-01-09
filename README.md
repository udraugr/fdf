### [RU][1] Описание проекта на русском
[1]: https://github.com/udraugr/fdf/blob/master/README.md#fdf---%D0%BE%D1%82%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BA%D0%B0%D1%80%D1%82%D1%8B-%D0%B2%D1%8B%D1%81%D0%BE%D1%82 "RU"
### [EN][2] Description of the project in English
[2]: https://github.com/udraugr/fdf/blob/master/README.md#fdf---altitude-map-display "EN"

# FDF - отображение карты высот
В этом проекте мы знакомимся с компьютерной графикой. Нашей задачей было считать файл с картой высот,
проверить его на отсутствие ошибок(например: карта это матрицей NxM) и нарисовать карту высот.
Проект был выполнен в Школе Программирования 21 (филиал французкой школы "Ecole 42").

# Сборка проекта:
Для компиляции потребуется установить и настроить framework OpenGL и AppKit. 
Для того, чтобы собрать проект, необходимо зайти в корневой каталог проекта и в терминале прописать команду **make**

# Запус проекта:
**./fdf [map]** (несколько сцен есть в папке test_maps).

# Управление:
* **ESC** закрыть программу
* Стрелочки **вверх/вниз** премещают карту вверх/вниз по оси OY
* Стрелочки **влево/вправо** перемещают карту влево/вправо по оси OX
* *На numpad* цифры **1** и **2** вращает карту по оси OZ против и по часовой стрелке
* **4** и **5** -- по оси ОX
* **7** и **8** -- по оси ОY
* **+** и **-** -- приближает и отдаляет карту
* **6** и **9** -- увеличивает и уменьшает разницу высот карту (добавляет и отнимает высоту точкам выше среднего значиния) 

## test_maps/42.fdf
![42.fdf](https://github.com/udraugr/fdf/raw/master/./42.png)

## test_maps/pyramide.fdf
![pyramide.fdf](https://github.com/udraugr/fdf/raw/master/./pyramide.png)

## test_maps/pylone.fdf
![pylone.fdf](https://github.com/udraugr/fdf/raw/master/./pylone.png)

## test_maps/mars.fdf
![mars.fdf](https://github.com/udraugr/fdf/raw/master/./mars.png)

### Примечание:
Этот проект полностью написан в школе программирования 21, и принадлежит ей.


#  FDF - altitude map display
In this project we are introduced to computer graphics. Our task was to read the file with a map of heights,
check it for errors (for example: the map is an NxM matrix) and draw a map of heights.
The project was done at the School of Programming 21 (a branch of the French school "Ecole 42").

# Build the project:
To compile, you will need to install and configure the OpenGL framework and AppKit.
In order to build the project, you need to go to the root directory of the project and in the terminal type the command **make**

# Run the project:
**./fdf [map]** (several scenes are in the root folder).

# Management:
* **ESC** close the program
* Arrows **up/down** move the camera up / down along the OY axis
* Arrows **left/right** move the camera left / right along the OX axis
* *On numpad* digits **1** and **2** rotate camera along the OZ axis counterclockwise and clockwise
* **4** and **5** -- along the OX axis
* **7** and **8** -- along the OY axis
* **+** and **-** -- zooms in and out the map
* **6** and **9** -- increases and decreases elevation differences on the map (adds and subtracts elevation to points above the average value) 

## test_maps/42.fdf
![42.fdf](https://github.com/udraugr/fdf/raw/master/./42.png)

## test_maps/pyramide.fdf
![pyramide.fdf](https://github.com/udraugr/fdf/raw/master/./pyramide.png)

## test_maps/pylone.fdf
![pylone.fdf](https://github.com/udraugr/fdf/raw/master/./pylone.png)

## test_maps/mars.fdf
![mars.fdf](https://github.com/udraugr/fdf/raw/master/./mars.png)

### Note:
This project is done at programming School 21, and belongs to it.
