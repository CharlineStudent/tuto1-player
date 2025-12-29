# Tuto 1 – Player et déplacements
@tutorial

## Étape 1 : Créer le personnage
@step

Insère le bloc suivant.

```blocks
let player = sprites.create(img`
    . . 2 2 2 . .
    . 2 2 2 2 2 .
    . 2 2 2 2 2 .
    . . 2 2 2 . .
`, SpriteKind.Player)
