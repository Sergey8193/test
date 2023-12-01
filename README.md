# 'Stellar Burgers' unit-tests

UNIT TESTING A TRAINING SERVICE
[**«STELLAR BURGERS»**](https://stellarburgers.nomoreparties.site)


## Description

Project uses
- Java 11
- JUnit 4.13.2
- Jacoco 0.8.7
- Mockito 3.12.4


## Running auto tests

**Repository cloning** (```git clone https://git@github.com:Sergey8193/Diplom_1.git```)
 ```
git clone https://git@github.com:Sergey8193/Diplom_1.git
```

**Running tests and generating JaCoCo coverage report** (```mvn clean verify```)
```   
mvn clean verify
```

**preparing JaCoCo agent** (```mvn jacoco:prepare-agent```)
``` 
mvn jacoco:prepare-agent
```

**generating JaCoCo coverage report** (```mvn jacoco:report```)
``` 
mvn jacoco:report
```


## Project Tree

```
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
