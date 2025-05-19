# Elektronische Last

Hierbei handelt es sich um einen elektronische Last, die im Bereich von etwa 5-30 V 0-5 A mit einer maximalen durchschnittlichen Leistung von 100 W arbeitet. Zum einfacheren Debugging wurde die Funktion auf verschiedene Leiterplatten aufgeteilt. Es gibt eine Hauptplatine, die die Leistung der Quelle abnimmt und 3 Platinen (eine Platine mit Sollbruchstellen) für einen Signalgenerator (die Last kann auch gepulste Lasten aufnehmen), Hilfsspannungen und einen ersten Protoyp der Leistungsstufe inklusive Stromregelschleife.

Es können extern auch dynamische Belastungskurven vorgegeben werden. Ein Lüfter wird ab einer Grenztemperatur zugeschaltet und ab etwa 90-95°C wird die Last mit entsprechender Temperaturhysterse getrennt

Die Schaltung ist komplett "analog", besitzt also keinen Mikrocontroller.

## Schaltplan

### Hauptplatine

![Haupt-Schaltplan 1](images/main/main-1.png)
![Haupt-Schaltplan 2](images/main/main-2.png)
![Haupt-Schaltplan 3](images/main/main-3.png)
![Haupt-Schaltplan 4](images/main/main-4.png)

### Signalgenerator + Hilfsspannungen + Prototyp der Leistungsstufe

![Hilfs-Schaltplan 1](images/helper/helper-1.png)
![Hilfs-Schaltplan 2](images/helper/helper-2.png)
![Hilfs-Schaltplan 3](images/helper/helper-3.png)

## Layout

### Hauptplatine

![Layout](images/main/layout.png)

### Signalgenerator + Hilfsspannungen + Prototyp der Leistungsstufe

![Layout](images/helper/layout.png)

## 3D

### Hauptplatine

Hier fehlt der Kühlkörper, der über den BJTs innerhalb der weißen Markierungen sitzt.
![3D](images/main/3D.png)

### Signalgenerator + Hilfsspannungen + Prototyp der Leistungsstufe

![3D](images/helper/3D.png)
