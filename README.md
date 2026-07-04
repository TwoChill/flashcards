# FlashCards

Kleine terminal-scripts om informatie te oefenen en te onthouden. Ze draaien ook prima in een mobiele
Python-interpreter, handig om onderweg even iets te trainen.

Geen installatie van externe packages nodig — alleen Python 3.7 of nieuwer (alles draait op de
standaardbibliotheek).

## Aan de slag

```
git clone https://github.com/TwoChill/flashcards.git
cd flashcards
```

Start een van de recallers (vervang `PAD` door het pad naar de map waarin je kloonde):

**Boolean Expression Recaller**
```
python PAD/Python_Boolean_Expression_Recaller/Python_Boolean_Expression_Recaller.py
```

**Class Drills Recaller**
```
python PAD/Python_Class_Drills_Recaller/Python_Class_Drills_Recaller.py
python PAD/Python_Class_Drills_Recaller/Python_Class_Drills_Recaller.py reverse
```

**Multiplication Table Recaller**
```
python PAD/Multiplication_Table_Recaller/Multiplication_Table_Recaller.py
```

## Hoe het werkt
* Je kiest welke vragen je wilt oefenen.
```
=======================
Boolean Expression Quiz
=======================

    Which do you want to recall?
    ===========================

     1. All Questions
     2. Or
     3. And
     4. Or & And
     5. Not(_or_)
     6. Not (_and_)
     7. Not(_or_) & Not (_and_)
     8. Not Equal (!=)
     9. Equal To (==)
    10. Not Equal (!=) & Equal To (==)
```

* Typ je antwoord om te zien of het klopt.
```
Question:	-->	False and True
Evaluates to?:	-->	False


				CORRECT!
				========
```
* Typ ```quit``` of ```result``` om te stoppen en/of je resultaten te zien.
```
Question:	-->	True and False
Evaluates to?:	-->	quit

      ==================================
      Boolean Expression Quiz -  Results:
      ==================================
     |       Correct Answerd:    2      |
     |       Incorrect Answerd:  0      |
     |       Total Questions:    4      |
     |                                  |
     |       Your Grade:         5      |
      ==================================
```

## Multiplication Table Recaller
* Kies welke tafel je wilt oefenen.
```
==============================
Type "quit" or "result to see your grade!
==============================

Which multiplication table to recall? :> 10
```
* Kies daarna je vector (hoe hoog ga je in de tafel?).
```
Up to which vector? :> 200
```
* Oefen zoveel je wilt.
```
Recalling the table of 10 with a vector of 200
==============================================


What is 10 * 61?
:> 610

That's correct!
===============
```
* Typ "quit" of "result" om te stoppen.
```
What is 103 * 10?
:> quit

Your grade is a 10 / 10

=======================


Thank you for trying!
```