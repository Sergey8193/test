# 'Stellar Burgers' unit-tests

UNIT TESTING A TRAINING SERVICE
[**«Stellar Burgers»**](https://stellarburgers.nomoreparties.site)

## Description
Unit testing a training service 'Stellar Burgers'

Project uses
- Java 11
- JUnit 4.13.2
- Jacoco 0.8.7
- Mockito 3.12.4

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
