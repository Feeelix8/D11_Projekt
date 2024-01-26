# MapSnap

## Modul D11

### Team ALO

* Ilkkan Alphan
* Eric Langer
* Felix Ossmann

MapSnap ist eine moderne Android-App, die es Benutzern ermöglicht, Notizen mit spezifischen Standortdaten zu verknüpfen. Egal, ob Sie Orte für zukünftige Reisen markieren oder Erinnerungen an besondere Orte festhalten möchten, MapSnap bietet eine intuitive und nahtlose Möglichkeit, Ihre Welt zu kartieren.

## Technologien

Dieses Projekt nutzt eine Reihe moderner Technologien und Praktiken:

- **Kotlin:** Die gesamte App ist in Kotlin geschrieben.
- **Android Jetpack:** Für eine robuste und wartbare App-Architektur.
- **Room Database:** Für effiziente und strukturierte Datenhaltung.
- **Google Services:** Play Services, Location Services, API für Open Weather App

## Screen-Design

![Hauptbildschirm](https://i.postimg.cc/Jzc18zzH/Mainscreen.png)
![Notizenliste](https://i.postimg.cc/LX7SDqNw/Notizenliste.png)
![Notizenbearbeitung](https://i.postimg.cc/pdcyNLsY/Notizenbearbeitung.png)

## Installation

Klonen Sie das Git-Repository und importieren Sie es in Android Studio:
```
git clone https://github.com/Feeelix8/MapSnap
```

Den korrekten Pfad zur SDK in **local.properties** eintragen (jeweiligen Pfad ändern):
```
sdk.dir=C\:\\Users\\BENUTZERNAME\\AppData\\Local\\Android\\Sdk
```

Für das Emulated Device muss eine Location gesetzt werden, damit die Wetter und GPS Features funktionieren kann.

## Starten der Applikation

Vor dem Starten der App, empfehlen wir den Storage und Cache für die App "MapSnap" zu löschen.

Hierzu navigieren Sie bitte zu: Settings >> Apps & notifications >> MapSnap

1. Klicken Sie auf **Force Stop**
2. Navigieren Sie zu **Storage and Cache**
3. Klicken Sie auf **Clear Storage** und anschließend auf **clear cache** (siehe Screenshot)
4. Nun können Sie die App eindwandfrei starten

![Cache und Stroge löschen](https://i.postimg.cc/WpXm6zdN/mapsnap-cache.png)

## Kontakt

Für weitere Fragen oder Feedback kontaktieren Sie uns bitte unter [support@mapsnap.com](mailto:support@mapsnap.com).

