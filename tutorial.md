# Labirynt

## Wstęp @unplugged

Witaj w MakeCode Arcade! Stwórzmy grę, w której Twój gracz musi uciec z labiryntu, zanim skończy się czas!

## Krok 1

Najpierw stwórzmy naszego gracza. Znajdź blok `||variables(sprites):set mySprite to||` w sekcji `||sprites:Sprites||`. Przeciągnij go do bloku `||loops:on start||`.

```blocks
let mySprite: Sprite = sprites.create(img`
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
`, SpriteKind.Player)
