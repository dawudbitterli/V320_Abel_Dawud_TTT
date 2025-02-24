# V320 Projektarbeit TicTacToe
 
 Autoren:
 : David Bitterli
 Abel Solomon

## Produkvision TicTacToe

Die Üblichen "TicTacToe" varianten kennt jeder, wer seine Symbole in eine 3er Reihe gebracht hat, gewinnt die Partie. Für uns ist das zu anspruchslos, keine Partien die in einer Patt Situation enden, deshalb haben wir es und zur Herausforderung gemacht das bekannte Kindheitsspiel zu optimieren. 

Ein "TicTacToe", welches in verschiedenen grössen wie 3x3, 5x5 oder auch 7x7 gespielt werden kann und bei dem es an neuen Strategien bedarf. 

Wir wollen den Kinderspiele-Klassiker nun als digitale und inovative Version an die Spielebegeisterten geben und die Nostalgie zurück bringen.

Das spielen auf einem grösseren Feld wie beispielsweise 7x7 bringt den Vorteil, das der beginnende Spieler nicht den Vorteil hat, durch gezielte Strategien jedes Spiel zu gewinnen. Es bringt auch den Vorteil, dass man weniger häufig in ein Unentschieden gerät. 

Mit unserem Endprodukt wollen wir diese bekannten Probleme aus der Welt schaffen und neues Leben in das Spiel einbringen.

## Produkt Backlog

|Userstories|Beschreibung|Akzeptanzkriterien|
|-----------|------------|------------------|
|**1. Individuelle Spielgrösse**|Ich kann eine vorgegebene Spielfeldgrösse auswählen um das Spiel individuell auf meine Bedürfnisse anzupassen| Der Spieler kann vor dem Beginn des Spiels die grösse wählen und wird korrekt angezeigt|
|**2. Spielzug tätigen**|Ich kann wenn ich an der Reihe bin meinen Spielzug tätigen|Das Symbol des Spielers wird auf dem Spielfeld angezeigt|
|**3. Unveränderbares Spielfeld**|Wenn der Spielzug getätigt wird kann das Spielfeld in dem Zustand in dem es sich befindet nicht mehr verändert werden|Der Spielzug kann ==unmöglich rückgängig== gemacht werden|
|**4. Automatische Spielzugübergabe**|Sobald der Spielzug eines SPielers getätigt wurde und das Spielfeld mit dem neu hinzugefügten Symbol gespeichert ist, ist automatisch der andere Spieler an der Reihe|Die Spielzüge werden automatisch übergeben|
|**5. Spielende bei Patt**|Wenn ein Unentschieden erspielt wird, wird ein Text ausgegeben und die Runde gestoppt|Bei Patt kann kein Spielzug mehr gespielt werden und der text wird automatisch ausgegeben|
|**6. Spielernamen**|Die Spieler können sich spitznamen geben vor dem beginn des Spieles|Die abfrage für die Spitznamen geschieht vor der Auswahl der Brettgrösse und werden korrekt angezeigt|
|**7. Zeiterfassung**|Die summierte Zeit die ein Spieler über alle Spielzüge hinweg in der aktuellen Partie benötigt wird|Die Zeit wird in Sekunden korrekt angezeigt und wird nur dann gezählt wenn ein Spieler am Zug ist fortlaufend aktualisiert|
|**8. Farbige Symbole und Namen**|Die Spieler bekommen eine zufällige Farbe zugeteilt die deren Namen und Symbole einfärbt|Die Farben werden zufällig von festgelegten Farben genommen und werden korrekt angezeigt und sind klar unterscheidbar|
|**9. Text für Gewinner**|Wenn ein Spieler eine Runde gewonnen hat, wird sein Name mit einem Text angezeigt|Es wird der Name des Gewinners abgebildet und des kann kein Süielzug mehr gespielt werden|
|**10. Spielabbruch**|Das Spiel kann jederzeit beendet werden durch eine spezifische Taste|Das SPiel kann nur mit der einen Taste beendet werden und führt in das Menü zurück. Der Spielstand wird gelöscht|