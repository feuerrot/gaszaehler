# Gaszählersensor

Dieses Projekt dient dazu, einen über Doppelader angeschlossenen Sensor am
Gaszähler an einen S0-Eingang anzubinden

Der Gaszähler hat in der 6 der dritten Nachkommarstelle eine reflektierende
Scheibe, was es ermöglicht, den Gasverbrauch auf jeweils 1L genau zu
messen.

Da bis zum Gaszähler nur eine Doppelader liegt, schaltet der CNY-70 über
einen Vorwiderstand einen Transistor, wodurch mehr Strom verbraucht wird.
Diese Stromdifferenz wird am anderen Ende der Doppelader dann in ein
binäres Signal übertragen und steht über einen Optokoppler potentialfrei
zur Verfügung.

## Schaltplan

### Sensor
![Schaltplan des Sensors am Gaszähler](img/schaltplan_sensor.png)

### Konverter
![Schaltplan des Konverters](img/schaltplan_s0-converter.png)

### Beides
![Komplettschaltplan](img/schaltplan.png)

## Layout

### Sensor
![Layout des Sensors am Gaszähler](img/layout_sensor.png)

### Konverter
![Layout des Konverters](img/layout_s0-converter.png)

### Beides
![Komplettlayout](img/layout.png)
