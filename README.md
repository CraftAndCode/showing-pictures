# Displaying pictures

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
Hello! Today you're going to learn how to display pictures with your Micro:bit!

## Step 1 @showDialog
Your Micro:bit's display  has 25 LEDs that can be turned on and off. That means there are 33,554,432 possible combinations! 
  
To learn more about LEDs, [watch this video](https://www.youtube.com/watch?v=qqBmvHD5bCw&list=PLMMBk9hE-SeqDYtw9pGNPsQ10V_EGMyGe&index=1)!

## Step 2 @showHint
### Displaying pictures
Let's try creating an image. First, add a ``||basic.show leds||`` block from the toolbox.  
```hint
This is what it looks like:
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
### Displaying pictures
Place this block inside the ``||basic.forever||`` block and click on the squares until you see a picture you like.
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
### Using ready-made icons
There are also some ready-made icons to choose from. These can be displayed with the help of a ``||basic.show icon||`` block. Try it now!  
  
Replace the ``||basic.show leds||`` block with ``||basic.show icon||`` block from your toolbox and select one of the 40 icons.
```hint
Your code should look like this:
```

```block
basic.forever(function () { 
    basic.showIcon(IconNames.Heart)
})
```
## Step 5
### Displaying arrows
A ``||basic.show arrow||`` block is a simple way to show an arrow pointing in one of eight directions.
  
Try it for yourself and then click ``|Next >|`` to challenge yourself!
```block
    basic.showArrow(ArrowNames.North)
```

## Step 6 @showHint
### Challenge 1
Use everything you've learned today to display these three pictures:

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture1.png)  

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture2.png)  

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture3.png)

## Step 7 @showDialog

### Displaying animations
If the pictures are shown one after another, this is called an animation and can give the illusion of movement.
```hint
An example of animation
```
![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/Heartbeat.gif)


## Step 8 @showHint
### Displaying animations
Let's display the animation of a heartbeat! This animation has only two pictures in it, but that's enough, as they are repeated ``||basic.forever||``.
```blocks
})
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showIcon(IconNames.SmallHeart)
})
```

## Step 9 @showHint
### Challenge 2
Draw pictures and try to match the animation. 
```hint
```
![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/Pulse.gif)

## Step 10
Completed all the challenges? Excellent! Now you know all about displaying pictures and animations! Download your code to Micro:bit and show  your friends and family!

## Answers @showDialog
### Answer: Tutorial 1.1
```blocks
basic.showLeds(`
    . # . # .
    # . # . #
    # . # . #
    . . # . .
    # # # # #
    `)
```
### Answer: Tutorial 1.2
```blocks
basic.showIcon(IconNames.Butterfly)

```
### Answer: Tutorial 1.2
```blocks
basic.showArrow(ArrowNames.SouthEast)

```
### Answer: Tutorial 2
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
