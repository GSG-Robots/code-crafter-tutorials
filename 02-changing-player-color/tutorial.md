# Spielerfarbe ändern

1. Um die Spielerfarbe zu ändern, kannst du `set_player_color` verwenden. `set_player_color` nimmt ein Argument welches die Farbe des Spielers beschreibt. Hier verwenden wir zunächst `Color.BLACK` um den Spieler schwarz anzuzeigen.  

    Das sieht dann so aus:
    ```python
    set_player_color(Color.BLACK)
    ```

    > [!TIP]
    > Dein Code sollte jetzt so aussehen:
    > ```python
    > from prgrmr import *
    >
    > set_player_color(Color.BLACK)
    >
    > run()
    > ```

    Wenn du auf das "Play"-Symbol oben rechts im Editor klickst, wird der Code ausgeführt und der Spieler wird jetzt schwarz angezeigt.  

2. Versuche nun, den Spieler in einer anderen Farbe anzuzeigen. Ändere die Farbe des Spielers in rot, indem du `Color.RED` als Argument für `set_player_color` verwendest.

    ```python
    set_player_color(Color.RED)
    ```
    
    > [!TIP]
    > Die weiteren Verfügbaren Farben sind:
    > * `Color.BLUE`
    > * `Color.GREEN`
    > * `Color.YELLOW`
    > * `Color.PURPLE`
    > * `Color.ORANGE`
    > * `Color.CYAN`
    > * `Color.MAGENTA`
    > * `Color.BROWN`
    > * `Color.WHITE`

    Damit kannst du den Spieler in jeder Farbe anzeigen, die du möchtest.

## Zusammenfassung

Super! Du hast gelernt, wie du die Farbe des Spielers ändern kannst. 

Du kannst die Farbe des Spielers in jeder Farbe anzeigen, die du möchtest, indem du `set_player_color` verwendest, und dabei die gewünschte Farbe in Klammern übergibst.

Die Farben, die du verwenden kannst, sind:

* `Color.BLACK`
* `Color.RED`
* `Color.BLUE`
* `Color.GREEN`
* `Color.YELLOW`
* `Color.PURPLE`
* `Color.ORANGE`
* `Color.CYAN`
* `Color.MAGENTA`
* `Color.BROWN`
* `Color.WHITE`
