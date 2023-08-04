# Easy scoreboards
### A datapack that will make creating dynamic scoreboards very simple!
# Датапак позволяющий просто создавать динамические скорборды

# (English)
# Usage📝
In tick function run function 0.

In function 0 write:
```mcfunction
data merge storage main {id:"",name:"",name2:"",value:"",objective:""}
function test:score/1 with storage main
```
id — scoreboard name (if id = "time", linked score = #time info)

name_pre, name_post — visual name before/after(You can use non-breaking space) 

value — string number/scoreboard value.

objective — scoreboard to display dynamic string.

# (Русский)
# Использование📝
В тик функции запустите функцию 0.

В функции 0 напишите:
```mcfunction
data merge storage main {id:"",name:"",name2:"",value:"",objective:""}
function test:score/1 with storage main
```
id — имя скорборда, хранящего значение (если id = "time", привязанный счёт = #time info)

name_pre, name_post — отображаемое имя до/после(можно оставить пустым, использовать неразрывный пробел и использовать форматирования §)

value — номер строки/значение скора.

objective — скорборд в котором отображается строка.


