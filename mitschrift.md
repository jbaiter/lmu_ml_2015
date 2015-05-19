# Sitzung 1, 29. April 2015

## Lösungen Übungsblatt

### 1-1: Linear Algebra

a) - 7
   - (2 2 1
      4 4 2
      2 2 1)
   - (1 5
      2 7
      1 4)
   - (7 5 4
      2 1 1)
   * (6
      5)
   - (6 5)

   Warum gilt nicht A C = C A^T? Kein Kommutativgesetz! Es gilt lediglich
   AC^T = C^T A^T. Außerdem gelten das Assoziativ- und das Distributivgesez.
   Das ist wichtig bei Effizienzfragen.

b) ( 2/3  -1/3
    -1/3   2/3)

c) (1 0 0
    0 1 0
    0 0 1) <- Identitätsmatrix

    Am einfachsten per Gram-Schmidt-Verfahren.

Muss scheinbar nicht wirklich für die Klausur gelernt werden, mehr die
Konzepte wichtig.


### 1-2 Wiederholung Vektor Calculus

a) sum(i=1...n)xi/dxj = (n - 1) * 0 + dxj/dxj = 1
   → Vektor nur mit einsen

b) x^Tx/dxj = (n - 1) * 0 + dxj^2/dxj = 2xj

c) d(x - mu)^2 = (d(x - mu)^T * (x - mu))/dxj = dsum(i=1..n(xi - mui)^2)/dxj = 2(xj - muj) = 2(x - mu)


### 1-3 Boolsche Funktion als Perceptron

b Hyperebenengleichung: h = w0 + w1*x1 + w2*x2
   Für h=0 -> x2 = w0/w2 - (w1/w2)*x2
   Bei w2=1 folgt w0 = -1/2; w1 = -1


### 1-4 Perceptron Lernregel anwenden

sample-based-learning: Immer einen einzelnen Punkt suchen, anhand dem lernen,
weiter bis fehler 0 ist.

Musterbasierter Ansatz: Immer nur einen einzelnen Punkt
(==== sample-based === pattern based?)

Muster -> Feature + Label

Gradient-Descent: Immer alle misklassifizierten!

Vorteil von sample-basiert: Schneller, da nicht immer das ganze Modell angepasst
werden muss.
