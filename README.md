# JanisFelixBot
<img src="https://raw.githubusercontent.com/Sonixier/JanisFelixBot/master/JanisFelixBot/pictures/icon.jpg" width="100" height="100" />
# PROJEKT EINGESTELLT / CODE ZUR WEITERENTWICKLUNG VERFÜGBAR
Ich finde es sehr schade verkünden zu müssen, dass JanisFelixBot nun eingestellt wird. Die Entwicklung mit Felix war eine schöne Zeit, aber er hat leider, was ich sehr bedauere, die Entwicklung aufgrund eines lächerlichen Streites verlassen. Der Code ist für jeden frei verfügbar.
Falls ihr also Bock habt, drückt einfach den Fork Knopf, und schon kanns losgehen!

Peace, Janis



# Installation

Python 3 wird vorausgesetzt.

1. Auf Github drücke auf ``Clone or Download`` und dann auf ``Download ZIP``. Nun gehe auf https://github.com/Flixlix/telegram-chatter und mache das Gleiche. Nun entpacke beide ZIP Dateien und kopiere den Inhalt von ``Downloadverzeichnis\telegram-chatter-master`` in den Ordner ``Downloadverzeichnis\JanisFelixBot-master\JanisFelixBot``.
2. Ubuntu: Starte ein Bash-Fenster im Ordner ``Downloadverzeichnis\JanisFelixBot-master\JanisFelixBot`` und gebe folgenden Befehl ein: ``pip3 install -r requirements.txt``.   
   Windows: Starte ein cmd-Fenster Im Verzeichnis ``Downloadverzeichnis\JanisFelixBot-master\JanisFelixBot`` und gebe folgenden Befehl ein: ``py -m pip install -r requirements.txt``   
3. Ersetze nun die folgende Werte direkt am Anfang der Bot.py:   
`bot = TelegramBot("`Hier muss dein Telegram Bot-Token rein`")`   
`admingroup = `Hier muss die ID der Admingruppe rein   
  In die Admingruppe sendet der Bot Nachrichten wenn ein Nicht-Admin probiert etwas für Admins auszuführen.
4. Nun ersetze den Text der admins.txt mit deiner ID. Später können per /addadmin mehr Admins hinzugefügt werden.  
