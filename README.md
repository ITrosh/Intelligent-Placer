# Intelligent-Placer
## Постановка задачи
### Общее описание
В рамках данного проекта необходимо по поданной на вход фотографии нескольких предметов на светлой горизонтальной поверхности и многоугольнику понимать, можно ли расположить одновременно все эти предметы на плоскости так, чтобы они влезли в этот многоугольник.
### Выбор многоугольника
Многоугольник рисуется на белом листе формата А4 и фотографируется вместе с предметами.
### Алгоритм работы программы
На вход программа получает фотографию с несколькими предметами и белым листом формата А4, на котором изображён многоугольник. С помощью алгоритма программа решает, могут ли сфотографированные предметы влезть в нарисованный многоугольник. На выход программа отдаёт логическое значение:
+ *True* - если предметы могут влезть в многоугольник
+ *False* - в противном случае
### Требования
1. Фотометрические: угол наклона камеры 90 градусов, верхняя точка съёмки.
2. Расположение объектов на фотографии: объекты не могут перекрывать друг друга, могут быть расположены как в центре фотографии, так и на её границе, однако должны полностью помещаться на фотографии
3. Ограничение: число вершин многоугольника не должно быть больше 8
4. Один и тот же объект не может присутствовать на фото более одного раза.
## Поверхность
<p align="center">
    <img src="photos/surface.jpg" alt="surface"/>
</p>

## Предметы
В качестве предметов были выбраны:
<p align="center">
    <img src="photos/items/scissors.jpg" alt="scissors"/>
    Ножницы
</p>

<p align="center">
    <img src="photos/items/spander.jpg" alt="spander"/>
    Эспандер
</p>

<p align="center">
    <img src="photos/items/staple.jpg" alt="staple"/>
    Скрепка
</p>

<p align="center">
    <img src="photos/items/USB flash drive.jpg" alt="USB flash drive"/>
    Флешка
</p>

<p align="center">
    <img src="photos/items/marker.jpg" alt="marker"/>
    Маркер
</p>

<p align="center">
    <img src="photos/items/anti-stapler.jpg" alt="anti-stapler"/>
    Антистеплер
</p>


<p align="center">
    <img src="photos/items/line.jpg" alt="line"/>
    Линейка
</p>

<p align="center">
    <img src="photos/items/sharpener.jpg" alt="sharpener"/>
    Точилка
</p>

<p align="center">
    <img src="photos/items/glue stick.jpg" alt="glue stick"/>
    Клей-карандаш
</p>

<p align="center">
    <img src="photos/items/block of stickers.jpg" alt="block of stickers"/>
</p>
<p align="center">
     Блок стикеров
</p>

## Сбор данных
Тестовые изображения вместе с файлом разметки размещены [здесь](https://github.com/ITrosh/Intelligent-Placer/tree/develop/photos/test%20examples)
