# Easy scoreboards
### A datapack that will make creating dynamic scoreboards very simple!
# Датапак позволяющий просто создавать динамические скорборды

# (English)
# Usage📝
In tick function run function 0.

In function 0 write:
```
data merge storage main {id:"",name:"",name2:"",value:"",objective:""}
function test:score/1 with storage main
```
id — scoreboard name (if id = "time", linked score = #time info)

name, name2 — visual name before/after(You can use non-breaking space) 

value — string number/scoreboard value.

objective — scoreboard to display dynamic string.

# (Русский)
# Использование📝
В тик функции запустите функцию 0.

В функции 0 напишите:
```
data merge storage main {id:"",name:"",name2:"",value:"",objective:""}
function test:score/1 with storage main
```
id — имя скорборда, хранящего значение (если id = "time", привязанный счёт = #time info)

name, name2 — отображаемое имя до/после(Можно использовать неразрывный пробел)

value — номер строки/значение скора.

objective — скорборд в котором отображается строка.


