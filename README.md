# js--workshop-oop

Uppgift 2: Klassen Bankkonto

Definiera en klass med namnet “BankAccount”. Bankkontot ska ha attributen “owner” och “balance” 0.0 när instansen skapas. 
Varje Bankkonto ska även ha instansmetoderna:
 “deposit” som sätter in en viss summa från bankkontot 
 “withdraw” som tar ut en viss summa från bankkontot 
“getBalance” som skriver ut nuvarande saldo för bankkontot

Gör även en kontroll så att man inte kan gå minus på kontot!

Testa din klass genom att skapa en instans av klassen, d.v.s ett konto för en viss “owner”. Testa även att göra några insättningar och uttag, samt checka saldot.


/*
  TASK 2
    - Write a Car constructor that initializes `model` and `milesPerGallon` from arguments.
    - All instances built with Car:
        + should initialize with an `tank` at 0
        + should initialize with an `odometer` at 0
    - Give cars the ability to get fueled with a `.fill(gallons)` method
      + should take 'gallons' as an parameter which will take number of gallons as an argument
      + should add the gallons to `tank`.
    - STRETCH: Give cars ability to `.drive(distance)`. The distance driven:
        + Should cause the `odometer` to go up.
        + Should cause the the `tank` to go down taking `milesPerGallon` into account.
    - STRETCH: A car which runs out of `fuel` while driving can't drive any more distance:
        + The `drive` method should return a string "I ran out of fuel at x miles!" x being `odometer`.
*/
