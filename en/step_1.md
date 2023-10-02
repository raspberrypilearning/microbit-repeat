If you want something in your code to happen a **fixed** number of times, you can use a `repeat`{:class='microbitloops'} block.

You used a repeat block in the Sleep tracker project to repeat the animation twice.

```microbit
function zZ () {
    for (let index = 0; index < 2; index++) {
        basic.showLeds(`
            . . . . .
            . . . . .
            # # # . .
            . # . . .
            # # # . .
            `)
        basic.showLeds(`
            . . . . .
            # # # # .
            . . # . .
            . # . . .
            # # # # .
            `)
        basic.showLeds(`
            # # # # #
            . . . # .
            . . # . .
            . # . . .
            # # # # #
            `)
    }
}
```

- You can find the `repeat`{:class='microbitloops'} block in the `Loops`{:class='microbitloops'} menu in your Toolbox.