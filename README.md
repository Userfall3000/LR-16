# LR16

Кириченко Антон

ЭВТ-70

Игровой Движок: Unity.

Лабораторная работа №16

Тема: Разработка анимированного UI интерфейса

Цель: Разработать анимированный UI интерфейс

1.	Создание папок Anims, Scenes, Scripts и Sprities

_______________![image](https://user-images.githubusercontent.com/119228138/204796650-fcaf6a99-b029-4f5f-bc6c-ea9f0a98dcc5.png)

 
_______________Рис 16.1 Создание папок 

2.	Параметр Main Camera
 
_______________![image](https://user-images.githubusercontent.com/119228138/204796673-f621412b-ba49-427e-8011-307c40657083.png)

 
_______________Рис 16.2 Настройка параметра  Main Camera

3.	Параметр Canvas и его дочерние объекты BgImage, Title, Panel (так же SFX и Music), Play, Settings, Other, Quit, share и Shop
 
_______________![image](https://user-images.githubusercontent.com/119228138/204796700-5c229c8f-2858-4b8f-88af-9c3849d8727b.png)


_______________Рис. 16.3 Настройка объекта BgImage
 
 _______________![image](https://user-images.githubusercontent.com/119228138/204796721-5002c2a8-b9d8-4401-8fd4-4547a3ac8516.png)

 
_______________Рис. 16.4 Настройка объекта Title

_______________![image](https://user-images.githubusercontent.com/119228138/204796743-54245bf5-926e-4658-86de-ee18df608ef3.png)

_______________Рис. 16.5 Настройка объекта Panel

_______________![image](https://user-images.githubusercontent.com/119228138/204796761-06005fa7-d5bb-4d2b-9e2d-7c0217328a52.png)

_______________Рис. 16.6 Настройка объекта SFX

_______________![image](https://user-images.githubusercontent.com/119228138/204796807-fd55bcc6-c1f5-479b-b465-13052ec3a67c.png)
 
_______________Рис. 16.7 Настройка объекта Music

_______________![image](https://user-images.githubusercontent.com/119228138/204796848-a46aa7d5-52f1-4a0e-beb9-a65618f063d6.png)

_______________Рис. 16.8. Настройка параметра Play

_______________![image](https://user-images.githubusercontent.com/119228138/204796871-3f725ae0-08f7-4fd3-8a43-0866201ec2b0.png)


_______________Рис. 16.9 Настройка объекта Settings

_______________![image](https://user-images.githubusercontent.com/119228138/204796899-40251a81-2f67-493a-93c7-36220453d9c7.png)

_______________Рис. 16.10 Настройка объекта Other

_______________![image](https://user-images.githubusercontent.com/119228138/204796919-277a2705-2e66-4d60-94c0-5db92ed6e625.png)

_______________Рис. 16.11 Настройка объекта Quit

_______________![image](https://user-images.githubusercontent.com/119228138/204796943-e41f4755-83ab-46fa-9eeb-2656028948f4.png)

_______________Рис. 16.12 Настройка объекта share

_______________![image](https://user-images.githubusercontent.com/119228138/204796964-623f7e08-8a5e-4ef6-ae0b-2d07c8ba51ab.png)


_______________Рис. 16.13. Настройка объекта Shop

4.	Параметр EventSystem
 
_______________![image](https://user-images.githubusercontent.com/119228138/204796983-69cedb08-5632-4435-994e-6c5ffff277b7.png)


_______________Рис. 16.14. Настройка объекта EventSystem

```
5.	Скрипт MenuManager
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.Animations;

public class MenuManager : MonoBehaviour
{
    public GameObject Panel;
    void Start()
    {

    }        
 
    void Update()
    {
        
    }

    public void Settings()
    {
        Panel.GetComponent<Animator>().SetTrigger("Pop");
    }    
}
```

	Вывод: В ходе данной проделанной работы был разработан UI интерфейс. 
  
[16.zip][16.zip](https://github.com/Userfall3000/LR-16/files/10123408/16.zip)
