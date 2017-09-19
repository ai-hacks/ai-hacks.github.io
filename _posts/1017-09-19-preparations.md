---
layout: post
title: Vorbereitung auf den Großen Tag
categories: jekyll update
---

Pläne wurden geschmieded und erste Ziele festgelegt. Es soll ein Super-Waffe für die VAM Rebellen bei AT entwickelt werden um den Wahnsinningen Altag überleben zu können.

Es soll folgendes entwickelt werden:
<div style="text-align: center; font-size: 2em">
Sprachassistent ROBASO
</div>

# Grobes Ziel
Die Idee ist eine eigenständige Hardware zu bauen, die Sprachkommandos verarbeiten und mittels Audiausgabe auch auf diese Antworten kann, ganz von der Bauart eines HAL oder K.I.T.T

Mögliche Kommandos sind u.a.:
* Definiere ABBA => ABBA steht für Automatisierte Beihilfebearbeitung auf Arbeitsplatzcomputer
* Wer kennt sich mit Hibernate aus => Meister Brenk weis alles
* In welchen Team is Bastian => Bastian ist in AT3
* Was macht die Funktion VVgb => VVgb kümmert sich um Lebenslaufeinträgen von 

# Umsetzung
Als Hardware Basis wollen wir einen Raspberry mit externen Microphon u. Lautsprecher nutzen.

Software seitig benötigen wir ein speach2text system, dass am besten open source ist und auch offline arbeiten kann. Dabei ist uns schon [Poket Sphinx](https://github.com/cmusphinx/pocketsphinx) ins Auge gefallen.

Darauf aufsetzend gibt es z.B. auch schon Projekte wie [https://jasperproject.github.io/](https://jasperproject.github.io/).


