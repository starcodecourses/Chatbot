# Chatbot

## ToDo: 
- Kommentare loops Präsentation einarbeiten
- neues Feedbackformular für Schülerinnen erstellen 

## Zeitplan/Ablauf: 
1) Begrüßung und Rezept(siehe Hinweise Rezept.docx) - evtl. weglassen?
2) [Intro](instroduction.pptx) (Was ist ein Chatbot)
3) Python Syntax 1 (strings): [Slides](strings.pptx), [Notebook](strings.ipynb), [Lösungen](strings_lösungen.ipynb)
4) Python Syntax 2 (conditions): [Slides](conditions.pptx), [Notebook](conditions.ipynb), [Lösungen](conditions_lösungen.ipynb)
5) Python Syntag 3 (loops): [Slides](loops.pptx), [Notebook](schleifen.ipynb), [Lösungen](schleifen_lösungen.ipynb)
6) Hangman: [Notebook](hangman.ipynb), [Lösungen](hangman_lösungen.ipynb)
7) Python Syntax 4 (functions): [Slides](functions.pptx), [Notebook](functions.ipynb), [Lösungen](functions_lösungen.ipynb)
8) Gruppenarbeitsphase

## Stichpunkte zum Kursinhalt
- Im Chatbot-Kurs lernt ihr, wie man einen kleinen Bot schreibt, der mit euch kommunizieren kann – so wie Siri, nur einfacher.
- Der Kurs findet in Python statt.
- Ihr braucht weder Vorkenntnisse noch Computer mitbringen.
- Der Kurs dauert ein Wochenende (Freitag Nachmittag bis Sonnstag Nachmittag).
- Zuerst lernt ihr, ein einfaches Spiel zu programmieren (Hangman).
- Dann werdet ihr euren ganz eigenen Chatbot entwickeln, zum Beispiel:
    - Ein Rezeptbot, der euch beim kochen hilft.
    - Ein Chatbot, der mit euch ein Ratespiel spielt.
    - Ein Chatbot, der euch bei einer Reisebuchung hilft.
- Ihr könnt eurer Kreativität freien Lauf lassen. 😄

## genereller Überblick 
Ein Chatbot ist eine kleine künstliche Intelligenz, die sprachlich mit Menschen interagieren kann. Das schöne an Chatbots ist, dass sie sehr niederschwellig anfangen. Auch das folgende Python-Programm ist im Prinzip schon ein Chatbot:

`name = input("Hi! I'm Alex, the chatbot! What is your name?\n")`
`print(f"Nice to meet you, {name}!")`

In anderen Worten: Solange man die Funktionen input und print versteht sowie mit Variablen und Strings umgehen kann lässt sich bereits ein Chatbot programmieren. Ab dann lässt sich das Projekt skalieren. Beispiele für einfache Chatbot-Projekte sind:

- Ein Spiel, bei dem der Chatbot mit gezielten Fragen versucht, zu erraten, an welches Objekt aus einer Menge die*der Spieler*in denkt (z.B. ein Pokémon aus einer Datenbank von 800 möglichen, falls das noch hip ist)
- Persönlichkeitstests ('Welcher Harry Potter-Charakter passt zu dir?')
- Näher an der Echtwelt: Bestellvorgänge (z.B. jemand möchte eine Reise buchen und der Chatbot versucht über verschiedene Fragen herauszufinden, welche Buchung am besten passt)

In allen Fällen muss man strukturiert über den Dialog nachdenken und den kürzesten Weg durch den großen Baum möglicher Dialoge finden, um möglichst rasch und mit wenig Frustration zum Ziel zu kommen. Endliche Automaten und Entscheidungsbäume sind naheliegende theoretische Modelle, die dabei helfen.

Chatbots laden außerdem zum Nachdenken über künstliche Intelligenz ein. Die KI-Geschichte ist durchzogen von Chatbots, vor allem inspiriert durch den Turing-Test und Weizenbaums [ELIZA](https://en.wikipedia.org/wiki/ELIZA)-Programm.

Schließlich sind Chatbots in der Industrie wieder zunehmend beliebt–vermutlich vor allem, um Kosten zu sparen. Interaktionen mit Endkund*innen werden zunehmend durch Chatbots ersetzt, gerade was den 'first level support' angeht, also die initiale Aufnahme von Problemen. Wer selbst schon mal einen Chatbot programmiert hat, hat wahrscheinlich einen klareren Blick für die Potenziale und Tücken solcher Systeme, sodass ein Chatbot-Projekt auch zur digital literacy beiträgt.
