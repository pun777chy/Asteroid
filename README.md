# Asteroid

https://github.com/pun777chy/Asteroid/assets/6859320/3903deae-df26-403a-b621-154bd1097a33

- It is sample game project based on classic Asteroid made on Unity 2021.3.10f1.
- The project used Zenject framework for dependency injections and inversion of control. 
- As the sample is quite basic the project maintained simplicity while strictly follows SOLID principle practices.
- Zenject signals are used for uncoupled communication between classes.
- GameScene is loaded using Addressables.
- In the given build addressable has been deactivated for now but it is working with editor for testing since the Play Mode Script is "Use Asset Database"
- A UNIT test was also conducted to test the binding of AsteroidSpawner class(I am still working on it if I can add more tests).
- The project has one Controller which maintains the States of the the game and update the Views.
- **PLEASE IGNORE THE UI. UI programming is my experties but I had to plan to implement UI gracefully.
**
   PACKAGES ADDED
  - Zenject
  - Addressables
  - ZenjectTestFramework

   CHALLENGES
  - Since implementing the game mechanics was easy, most of my time spent was on designing architure.
  - **I kept every class implementation at it's basic level so it would be easy to understand.**

      BUILD
    Asteroids-Classic/Build/Asteroids-Classic.exe



