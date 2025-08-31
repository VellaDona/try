# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

Heading 1
=

heading 2
-

1. ordered list item
    * unordered list item
    * unordered list item
2. ordered list item
    - unordered list item
    - unordered list item
    - unordered list item
3. ordered list item
    + unordered list item
    + unordered list item
    + unordered list item
4. ordered list item

горизонтальная линия (три и более:_нижнее подчеркивание,*звездочка, -минус), 
****
----
___

перенос строки - 2 пробела в конце строки


абзац  - 2 раза энтер

курсив - *в звездочках*  или _нижнее подчеркивание_  
жирный **две звездочки** или  __два нижних подчеркивания__  
жирный курсив ***три звездочки*** или ___три нижних подчеркиваания___  


обратная кавычка \` подсвечивает код внутри
три обратные кавычки \``` или три тильды \~~~ сохраняет блок кода   
```
$a = 5;
$b = 5;
$c = $a + $b;
 ```

>цитата 
>>вложенная цитата

Ссылка кликабельная (встроенная)  
[text](http://google.com)

Images- put in the same folder separatealy in the root or create a folder with imgs, in the path show just this folder/name of picture with a slash /
![text](pics/5-2-car-model.webp)
HTML can be inserted to specify img SIZE  
<img src="pics/5-2-car-model.webp" alt="a car" width="200">

to make img a link  
[![Picture-link to Google](pics/5-2-car-model.webp)](http://google.com)
or  
<a href="http://google.com">
  <img src="pics/5-2-car-model.webp" alt="Picture-link to Google" width="300">
</a>

Tables

item  | value| quantity
:-----|:----:|:-------:
Phone | 200| 4
Piano | 300| 2
Computer | 800| 1

	Экранирование и спецсимволы
•	Символы: \* \_ \# \- \+ \! \[ \] \( \)
•	Пример: \*не курсив\* → *не курсив*

<!-- Это комментарий -->

Текст с сноской[^1].
[^1]: Сноска

Задачи (Checklists)
- [ ] Непроверено
- [x] Проверено

Все, что ниже GitHub не поддержал:  
1. Подчёркивание в чистом Markdown нельзя.
Но можно использовать HTML (он работает внутри Markdown):  
<u>Подчёркнутый текст</u>

2. Цвет текста тоже только через HTML:

<span style="color:red">Красный текст</span>
<span style="color:green">Зелёный текст</span>

3. Фон текста - опять же HTML:
<span style="background-color:yellow">Текст с жёлтым фоном</span>


