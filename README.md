# KI-projekt 


## PROJEKTBESCHREIBUNG: ##
Das Projekt  bezieht sich auf eine künstliche Intelligenz ,Die bearbeitet Audiodatei in Text.  
Dafür haben wir mit der Programmiersprache  python  Bearbeitet, mit hilfe mit tensor flow und anderen bibliotheken .
Wir haben anhang eines Dataset von AudioDatei einen Model trainiert . Dieses Model umwandel die Werte in dem AudioDatei in Zahlen,
diese werte  werden auch ungekehr in Buchstaben kovertiert. Damit können wir die Audiodatei  in  Textdatei . 
Das Model wird mit hilfe von einem Dataset trainiert. Unsere Programm wird mit dem muster  der Textúbersetzung trainiert.



## BIBLIOTHEKEN : ##

- Tensorflow war die verantwortliche Bibliothek für die Modelerzeugung 

* Pandas ist für die Dateiverwaltung zuständig 

* Jiwer wird den Werkzeug für die modelevaluation  verwendet . Jiwer Vergleich den Text das den Model erzeugt mit den korrekten Text  dass kommen sollte .

- It computes the minimum-edit distance between the ground-truth sentence and the hypothesis sentence of a speech-to-text API. The minimum-edit distance is calculated using the Python C module Levenshtein.


## PROJET ENTWICKLUNG: ## 
1)  Die Notwendige wurden  biblbliotheken in den Python datei importiert und installiert. 
2)  Der dataset wurde  von  https://data.keithito.com/data/speech/LJSpeech-1.1.tar.bz2
3) Data wurde mit Pandas Zugriffen
4) Dataei wurde normalisiert, mit einen format von datei name, extension... etc 
![DIagramm ](https://github.com/JOAQ223/AI-Projekt/edit/main/README.md)
Quelle,sorce = https://towardsdatascience.com/audio-deep-learning-made-simple-automatic-speech-recognition-asr-how-it-works-716cfce4c706
Wir brauchen die Datei zur  einem Format in Lange und Size, Chanel , etc, da das Model  ähnliche EingabeDatei erwartet , damit das ungefahr funkzionieren kann.
Falls die Dateiqualität unbenutzbar ist , dann sollte man mit Algorthmen für noise-removal algorithm.Damit man die  background noise elimineren kann.Danach können wir den  focus  zur dem  Lenguage audio werfennoise-removal algorithm to eliminate background noise so that we can focus on the spoken audio..

5) Vorbereitung von der variablen : Den Alphanet wurde zur integer Werte gemapt und dann in text zur datei ungewandelt.
6)Dateset wurde  mit python getrennt zwischen Training und  Test 
7)Das Model wird mit hilfe von einem Dataset trainiert. Unsere Programm wird mit dem muster  der Textúbersetzung trainiert.



## Anleitung zur Installation und Ausführung Ihres Projekts:

 1- Python  in den Rechner installieren von https://www.python.org/downloads/<br/>
 2-  JIwer  installieren `` pip install jiwer <br/>
 3-  Pandas Installieren https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html <br/>
 



## Teammitglieder:

Dieutchou, Ruben Chester <br/>
Monteagudo Subiria, Joaquin <br/>
Ngnindjeu Sonfack, Doriane Lovline <br/>
