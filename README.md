# Stellar Burgers unit-tests

Тестирование учебного сервиса, которая помогает заказать бургер в Stellar Burgers, покрытие её юнит-тестами. 

## Description

Project uses
- Java 11
- JUnit 4
- Jacoco
- Mockito

## Auto test launching

Clone the repository to local computer
 ```sh
git clone git@github.com:Sergey8193/Diplom_1.git
```

Running tests and generating JaCoCo coverage report
```sh   
mvn clean verify
```

## Project Tree

```bash
pom.xml
README.md
.gitignore
src
|-- main
|   |-- java
|   |   |-- praktikum
|   |   |   |-- stellarburgers
|   |   |   |   |-- model
|   |   |   |   |   |-- mock
|   |   |   |   |   |   |-- BurgerDataGenerator.java
|   |   |   |   |   |   |-- StabGenerator.java
|   |   |   |   |   |-- Bun.java
|   |   |   |   |   |-- Burger.java
|   |   |   |   |   |-- Database.java
|   |   |   |   |   |-- Ingredient.java
|   |   |   |   |   |-- IngredientType.java
|   |   |   |   |-- Praktikum.java
|-- test
|   |-- java
|   |   |-- praktikum
|   |   |   |-- stellarburgers
|   |   |   |   |-- model 
|   |   |   |   |   |-- BunTest.java
|   |   |   |   |   |-- BurgerTest.java
|   |   |   |   |   |-- DatabaseTestTest.java
|   |   |   |   |   |-- IngredientTest.java
|   |   |   |   |   |-- IngredientTypeTest.java
|   |   |   |   |-- UnitTestLauncher.java
```

## Completed tasks

Created auto unit tests for Bun, Burger, DatabaseTest, Ingredient and IngredientType classes
