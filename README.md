## 畫UML
### 教他UML
```
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
this code can draw UML,have you learned?
```

### 測試
```
Let's create a uml for anything you want
```
![image](https://user-images.githubusercontent.com/47078512/206760522-5c5db1af-934b-46be-b219-2b1616c1587f.png)


### 教他換顏色
```
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ff0000'}}}%% can change the color to red,have you learned?
```

### 測試
```
Let's change the color to light yellow
```
![image](https://user-images.githubusercontent.com/47078512/206760119-326bc510-05e7-46c8-a093-d0aecce88e21.png)

把他給的CODE包在![image](https://user-images.githubusercontent.com/47078512/206760890-f6bfa0fc-8788-4674-b4e4-5b9bd100e9ed.png)裡面

