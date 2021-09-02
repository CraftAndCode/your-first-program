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

A program or an algorithm is a list of operations required to perform a task. These operations are performed one by one, top to bottom.

## Step 2

Every program should have its beginning and its end. There are blocks that tell Micro:bit when to start your program. One of these is a ``||basic.forever||`` block. Can you see it on screen?

## Step 3 @showhint

let's program Micro:bit to say ' Hello! '. Search your toolbox to find this block: ``||basic.show string||`` and add it to your program.
```diffblocks
basic.forever(function () {
})
----------
basic.forever(function () {
    basic.showString("Hello!")
})
```
## Step 4

Ready? Wonderful! Now download your code to Micro:bit using the ``|Download|`` button (you may have to click ``|....|`` and pair your device the first time) and enjoy watching your first program in action!

## Step 5
### Do it yourself
Change the appearing text by editing text in the ``||basic.show string||`` block. 
```blocks
basic.forever(function () {
    basic.showString("Any other text")
})
```
## Step 6
### Do it yourself
Make text to show only once by replacing ``||basic.forever||`` with ``||basic.on start||``. Can you tell what's changed?
```blocks
basic.showString("Hello!")
```

## Step 7
Completed all the tasks? Great! You have learned to display text with Micro:bit!