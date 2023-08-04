# Easy-scoreboards
A datapack that will make creating dynamic scoreboards very simple!
function 1

# Usage
In tick function run function 0.

In function 0 write:
```
data merge storage main {id:"",name:"",name2:"",value:"",objective:""}
function test:score/1 with storage main
```
id — scoreboard name (if id = "time", linked score = #time info)

name — visual name (if name = Time:, your score will be look Time:<#id info score> (You can use non-breaking space) )

value — string number/scoreboard value.

objective — scoreboard to display dynamic string.



