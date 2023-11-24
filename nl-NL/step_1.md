Als je wilt dat iets in je code een **vast** aantal keren gebeurt, kun je een `keer herhalen`{:class='microbitloops'} blok gebruiken.

Je hebt een keer herhalen blok in het Slaap-monitor project gebruikt om de animatie twee keer te herhalen.

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

- Je vindt het `keer herhalen`{:class='microbitloops'} blok in het `Lussen`{:class='microbitloops'} menu in je Toolbox.
