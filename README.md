﻿Цель - описать механизм получения геоданных из OpenStreetMap

./code - примеры консольных программ на C#:
  - osmnode.cs - получить объекты-точки (вулканы, страны, города)
  - osmway.cs - получить объекты-линии (пустыни)
  - osmway-buildings.cs - получить дома (постройки) с номерами домов
    (добавлено 2017.10.30)

./geojson - примеры результатов
./geojson-buildings - примеры результатов


PS:
  - osmnode.cs, osmway.cs - исправлена некорректность с разбором чисел с плавающей запятой.
    (иногда могло срабатывать исключение из-за дефолтной культуры) (исправлено 2017.10.30)

Статья (OpenStreetMap как источник геоданных): http://habrahabr.ru/post/270513/

E-mail: apelserg@mail.ru
