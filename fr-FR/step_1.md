Si tu souhaites que quelque chose dans ton code se produise un nombre **fixe** de fois, tu peux utiliser un bloc `répéter`{:class='microbitloops'}.

Tu peux utiliser un bloc répéter dans le projet Suivi du sommeil pour répéter l'animation deux fois.

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

- Tu peux trouver le bloc `répéter`{:class='microbitloops'} dans le menu `Boucles`{:class='microbitloops'} dans ta boîte à outils.