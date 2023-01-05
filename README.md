# Övningar Javascript OOP 

Syftet med denna workshop är att få förståelse och öva färdigheter om OOP i Javascript. Javascript är inte i grunden ett objekt-orienterat språk utan ett prototypbaserat språk: Övningarna ska därför ge en grundförståelse hur OOP används med prototype inheritance, men går vidare till att du använder ES6 classes som förstahandsval för syntax. 

## Protoype inheritance

1. Vad menas med en objekts prototyp?

2. Vad menas med Prototype inheritance i Javascript

2. Vad gör en s.k konstruktor-funktion? Vad gör det reserverade ordet `new`?

3. Vad refererar `this` till?

4. Hur kan skapa metoder som delas med alla instanser som är skapade av konstruktorfunktionen?


### Övning Geometriska figurer med Prototype inheritance

1. Skapa en konstruktorfunktion `Shape` som initialiseras med tre egenskaper - `name`, `sides` och `sideLength`

2. Lägg till en ny metod som delas med alla `Shape`-instanser. Metoden heter calcPerimeter och bara beräkna omkretsen av den geomteriska figuren.

3. Skapa en ny instans av `Shape` och kalla den `square` med `sides`är 4 och `sideLength` är 5.

4. Anropa `calcPerimeter`på den skapade instansen `square` och se att bräkningen stämmer i utskriften. 

5. Testa att skapa en annan instans av `Shape`som kallas `triangle` med `sides`3 och `sideLength` 3. Anropa `calcPerimeter` på den instansen och se att beräkningen stämmer i utskriften.

## ES6 classes

### Övning Geometriska figurer med ES6 Classes

Skriv om övningen så att du istället för Prototype inheritance använder syntaxen för ES6 classes.

### Klassen Bankkonto

Definiera en klass med namnet “BankAccount”. Bankkontot ska ha attributen “owner” och “balance” 0.0 när instansen skapas. 
Varje Bankkonto ska även ha instansmetoderna:
 “deposit” som sätter in en viss summa från bankkontot 
 “withdraw” som tar ut en viss summa från bankkontot 
“getBalance” som skriver ut nuvarande saldo för bankkontot

Gör även en kontroll så att man inte kan gå minus på kontot!

Testa din klass genom att skapa en instans av klassen, d.v.s ett konto för en viss “owner”. Testa även att göra några insättningar och uttag, samt checka saldot.
