## 畫UML
### 教他UML
```
```mermaid
classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
```
this code can draw UML,have you learned?
```

### 測試
```
Let's create a uml for anything you want
```

### 教他換顏色
```
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ff0000'}}}%% can change the color to red,have you learned?
```

### 測試
```
Let's change the color to light yellow
```
![image](https://user-images.githubusercontent.com/47078512/206760119-326bc510-05e7-46c8-a093-d0aecce88e21.png)


