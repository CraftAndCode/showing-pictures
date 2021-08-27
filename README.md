# Showing pictures

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
Hello! Today you'll know how to display pictures with your Micro:bit!

## Step 1 @showDialog
The display of your Micro:bit has 25 LEDs that can be turned on and off. That means there are 33554432 possible combinations! 
  
To learn more about LEDs, [watch this video](https://www.youtube.com/watch?v=qqBmvHD5bCw&list=PLMMBk9hE-SeqDYtw9pGNPsQ10V_EGMyGe&index=1)!

## Step 2 @showHint
### Showing pictures
Let's try to create an image. First, add a ``||basic.show leds||`` block from the toolbox.  
```hint
It looks like this:
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
### Showing pictures
Place this block inside the ``||basic.forever||`` block and click on the squares to get a picture that you like.
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
There are also some ready-made icons to choose from. They can be displayed with the help of a ``||basic.show icon||`` block. Try it now!  
  
Replace the ``||basic.show leds||`` block with ``||basic.show icon||`` and select any of the 40 icons.
```hint
Your code should look like this:
```

```block
basic.forever(function () {	
    basic.showIcon(IconNames.Heart)
})
```
## Step 5
### Showing arrows
A ``||basic.show arrow||`` block is a simple way to show an arrow pointing to one of 8 directions.
  
Try it yourself and then click ``|>|`` to challenge yourself!
```block
    basic.showArrow(ArrowNames.North)
```

## Step 6 @showHint
### Challenge
Use everything you've learned today to display these three pictures:

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture1.png)  

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture2.png)  

![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/picture3.png)

## Step 7 @showHint

### Displaying animations
If the pictures are shown one after another it is called an animation and can give the illusion of movement.
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
### Challenge
Draw pictures and try to match the given animation. 
```hint
```
![](https://raw.githubusercontent.com/CraftAndCode/alien-pet/master/Pulse.gif)

## Step 10
Completed all the challenges? Cool! Now you know all about showing pictures and animations with Micro:bit!
