## Spis treści
* [Ogólne informacje](#ogólne-informacje)
* [Użyte technologie](#użyte-technologie)
* [Prezentacja](#prezentacja)

## Ogólne informacje
Program wykorzystuje algorytmy na liniową i potęgową transformację obrazów oraz 16 różnych algorytmów mieszania dwóch obrazów ze sobą.
<h3>Transformacja liniowa obrazów </h3>
Korekcja liniowa jasności dodaje stałą wartość b do każdej składowej punktu <br>

g(x, y) = α * f(x, y) + β <br>

 * α decyduje dodatkowo o kącie nachylenia prostej odwzorowania, <br>
 * β jest wartością zmiany jasności w zakresie [−255..255], <br>
 * g(x, y) jest wartością wejściową punktu o współrzędnych (x,y).
<h3>Transformacja potęgowa </h3>
Transformacja potęgowa wyrażona jest wzorem<br>

 v′(x, y) = c*v(x, y)^n <br>
 
 gdzie c i n są dodatnimi stałymi.
  Dziedziną tej funkcji jest przedział domknięty [0..1]
 <h3>Tryby mieszania</h3>
Algorytmy różnych trybów mieszania można znaleźć 
<a href="https://en.wikipedia.org/wiki/Blend_modes">tutaj</a>.
	
## Użyte technologie
Projekt został utworzony z wykorzystaniem:
* Język C#
* Visual Studio 2019

## Prezentacja programu
[![IMAGE ALT TEXT](https://img.youtube.com/vi/a8b5admvjpQ/0.jpg)](https://www.youtube.com/watch?v=a8b5admvjpQ "Photo editor")
