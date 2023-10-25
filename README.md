# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division

Metrika, pregled i statička analiza

LOC za kompletan projekat iznosi 153.

Ciklomatska složenost (dobijena uz pomoć ekstenzije Codalyze u okviru Visual Studio Code-a):
za metode evaluateExpression i Calculate iznosi 12 za Calculator.java,
za Start.java iznosi 3.

Kognitivna složenost:
za metode evaluateExpression i Calculate iznosi 14

Calculator.java - LOC=134, broj linija koda=188
Statička analiza je odrađena koristeći Sonarlint i pronađeni su sledeći code smell:
1. Move this file to a named package. [Ln 1, Col 1]
2. Add a private constructor to hide the implicit public one. [Ln 4, Col 14]
3. Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object". [Ln 18, Col 30]
4. Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 18, Col 30]
5. Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 24, Col 26]
6. Immediately return this expression instead of assigning it to the temporary variable "textResult". [Ln 70, Col 29]
7. Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 74, Col 25]
8. Remove this redundant jump. [Ln 183, Col 13]

Start.java - LOC=19, broj linija koda=26
1. Move this file to a named package. [Ln 1, Col 1]
2. Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 6, Col 10]
3. Replace this use of System.out or System.err by a logger. [Ln 8, Col 3]
4. Replace this use of System.out or System.err by a logger. [Ln 19, Col 5]
