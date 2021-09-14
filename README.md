# Your First Program
### @flyoutOnly true
```template
basic.forever(function () {
    
})

```

```blocks
basic.showString("Hello!")

```

## Step 0 @showDialog

Hello! Let's write our first program for Micro:bit!

## Step 1 @showDialog

A program or  algorithm is a list of the operations required to perform a task. These operations are performed one by one, from top to bottom.

## Step 2

Every program must have a beginning and an end. There are blocks that tell Micro:bit when to start your program. One of these is a ``||basic.forever||`` block. Can you see it on the screen?

## Step 3 @showhint

Let's program Micro:bit to say ' Hello! '. Search through your toolbox to find this block: ``||basic.show string||`` and add it to your program.
```diffblocks
basic.forever(function () {
})
----------
basic.forever(function () {
    basic.showString("Hello!")
})
```
## Step 4

Found it? Great! Now download your code to Micro:bit using the ``|Download|`` button (you may have to click ``|....|`` and pair your device the first time). Now sit back and watch your first program in action!

## Step 5
### Now it's your turn
Change the  text that's displayed by editing the text in the ``||basic.show string||`` block. 
```blocks
basic.forever(function () {
    basic.showString("Any other text")
})
```
## Step 6
### You can do it yourself
Make the text appear only once by replacing ``||basic.forever||`` with ``||basic.on start||``. Download your code again. Can you see what's changed?
```blocks
basic.showString("Hello!")
```

## Step 7
Finished all these tasks? Great! You've learned how to display text with Micro:bit!
