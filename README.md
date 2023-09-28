## Проект Easy paint
Проект написан на языке Python, модуль turtle

```v = 90```-скорость черепашки  

```step = 15``` - кол-во пикселей, на которое передвигается черепашка, при управлении клавиатурой

```
draw(x, y) -функция, осуществяющая перетаскивание черепашки, если зажать ее курсором
```


```
def move(x, y) - функция, которая поднимает перо при нажатии на экран
```


```def stepUp/Down/Right/Left(x, y)``` - функции, осуществляющие движение вверх, вниз, влево, вправо при нажатии стрелок  

### Функции изменения цвета пера при нажатии на соответсвующую кнопку
- SetRed - красный цвет, при нажатии на "R"
- SetBlue - синий цвет, при нажатии "B"
- SetGreen - зеленый цвет, при нажатии "G"
- SetOrange - оранжевый цвет, при нажатии "O"
- SetViolet - фиолетовый цвет, при нажатии "V"
- SetBlack - черный цвет, при нажатии "L"
- SetPink - розовый цвет, при нажатии "P"
- SetYellow - желтый цвет, при нажатии "Y"

При нажатии на кнопку "E" начинается заливка цветом, который назначен черепашке в данный момнет. При нажатии на кнопку "T" заливка завершается
