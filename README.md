# Kicker-Analyse – DBV Praktikum

Digitale Bildverarbeitung Praktikum, Universität Siegen, 2026, bei Prof. Michael Moeller


## Aufgabenstellung

Echtzeit-Analyse eines Tischkickers mittels Bildverarbeitung:

| Schritt | Modul                 | Beschreibung                                     |
| ------- | --------------------- | ------------------------------------------------ |
| 1       | `calibration.py`    | Kamerakalibrierung per Schachbrett               |
| 2       | `perspective.py`    | Perspektivtransformation (ArUco / Segmentierung) |
| 3       | `ball_detection.py` | Ballerkennung (HSV-Filter + Tracking)            |
| 4       | `speed.py`          | Geschwindigkeitsmessung in km/h                  |
| 5       | `score.py`          | Torerkennung & Spielstand                        |
