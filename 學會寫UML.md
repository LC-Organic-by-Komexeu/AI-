> 把他給的CODE包在![image](https://user-images.githubusercontent.com/47078512/206760890-f6bfa0fc-8788-4674-b4e4-5b9bd100e9ed.png)裡面
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

#### 測試
```
Let's create a uml for anything you want
```
![image](https://user-images.githubusercontent.com/47078512/206779567-4b0aec7c-db6a-4a07-a54e-c97f920a0796.png)


### 教他換顏色
```
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ff0000'}}}%% can change the color to red,have you learned?
```

#### 測試
```
Let's change the color to light yellow
```
![image](https://user-images.githubusercontent.com/47078512/206779531-742c4ecf-e27d-4563-a460-36adbfa87aa8.png)

#### 隨機測試
```
Let's create another uml and use any color you want
```
![image](https://user-images.githubusercontent.com/47078512/206779506-e1f67b5a-a768-47d7-bbf6-d4142cb19fa2.png)
