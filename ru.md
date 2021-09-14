# Отображение картинок

```template
basic.forever(function () {
    
})

```
```blocks
    basic.showIcon(IconNames.Heart)
    basic.showArrow(ArrowNames.North)
    basic.showLeds(`
        . # # # .
        # # # # #
        . # # # .
        . . # . .
        . # # # .
        `)
    basic.clearScreen()
```
## Step 0 @showDialog
Всем привет! Сегодня мы с вами узнаем, как отображать картинки с помощью устройства Micro:bit!

## Step 1 @showDialog
Дисплей устройства Micro:bit состоит из 25 светодиодов. Это значит, что он может отобразить 33,554,432 разных картинок! 
  
Чтобы узнать больше о светодиодах, посмотрите [видео](https://www.youtube.com/watch?v=qqBmvHD5bCw&list=PLMMBk9hE-SeqDYtw9pGNPsQ10V_EGMyGe&index=1)!

## Step 2 @showHint
### Отображение картинок
Давайте создадим наше первое изображение. Найдите блок кода ``||basic.показать светодиоды||`` в списке команд.  
```hint
Он выглядит вот так:
```
```block
basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
```
## Step 3
### Отображение картинок
Вставьте новый блок внутрь блока ``||basic.постоянно||``. Кликайте по квадратикам, чтобы включать и выключать светодиоды на дисплее. Обратите внимание, как меняется картинка в окне симулятора.
```hint
Картинка может выглядеть так:
```
```diffblocks
basic.forever(function () {
    
})
----------
basic.forever(function () {
    basic.showLeds(`
        . # . # .
        # . # . #
        # . . . #
        . # . # .
        . . # . .
        `)
})
```

## Step 4
### Отображение готовых картинок
Также, мы можем показать одну из 40 заранее заготовленных картинок. Такую функцию выполняет блок ``||basic.показать значок||``. Давайте воспользуемся им!  
  
Замените в коде блок ``||basic.показать светодиоды||`` на ``||basic.показать значок||`` и выберите картинку.
```hint
Теперь ваша программа может выглядеть вот так:
```

```block
basic.forever(function () { 
    basic.showIcon(IconNames.Heart)
})
```
## Step 5
### Отображение стрелочек
Блок ``||basic.показать стрелку направлением||`` - это ещё одна из команд, которые выводят на экран картинки.
  
Попробуйте использовать его самостоятельно. Когда будете готовы, нажмите ``|Далее >|``, чтобы выполнить самостоятельное задание!
```block
    basic.showArrow(ArrowNames.North)
```

## Step 6 @showHint
### Самостоятельное задание 1
Отобразите три приведённых картинки, используя новые команды, о которых вы сегодня узнали. 

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture1.png)  

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture2.png)  

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture3.png)

## Step 7 @showDialog

### Отображение анимаций
Если картинки быстро сменяют друг друга, это называется анимацией. Анимация создаёт иллюзию движения и используется, например, при создании мультфильмов.
```hint
Пример анимации на экране устройства Micro:bit.
```
![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/Heartbeat.gif)


## Step 8 @showHint
### Отображение анимаций
Давайте создадим нашу первую анимацию! Как мы уже знаем, в линейном алгоритме команды выполняются одна за одной, последовательно. Так как наш алгоритм выполняется ``||basic.постоянно||``, наша анимация будет воспроизводиться бесконечно.
```hint
Соберём приведённый образец кода, используя уже известные нам команды. огда будете готовы, нажмите ``|Далее >|``, чтобы выполнить самостоятельное задание!
```
```blocks
})
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showIcon(IconNames.SmallHeart)
})
```

## Step 9 @showHint
### Самостоятельное задание 2
Напишите программу, которая будет показывать на экране заданную анимацию. 
```hint
```
![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/Pulse.gif)


## Ответы @showDialog
### Ответ: Картинка 1
```blocks
basic.showLeds(`
    . # . # .
    # . # . #
    # . # . #
    . . # . .
    # # # # #
    `)
```
### Ответ: Картинка 2
```blocks
basic.showIcon(IconNames.Butterfly)

```
### Ответ: Картинка 3
```blocks
basic.showArrow(ArrowNames.SouthEast)

```

### Ответ: Анимация
```blocks
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.showLeds(`
    . . . . .
    . # # # .
    . # . # .
    . # # # .
    . . . . .
    `)
basic.showLeds(`
    . # # # .
    # . . . #
    # . . . #
    # . . . #
    . # # # .
    `)
basic.showLeds(`
    . . . . .
    . # # # .
    . # . # .
    . # # # .
    . . . . .
    `)
```

## Step 7
Все задания выполнены!