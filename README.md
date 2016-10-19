# OOAD-WEEK09 Homework
##Class Diagram
 ## ส่งงาน Class Diagram 5 ข้อ
* รูปที่ 1 Computer
```
@startuml

title Classes - Computer

class CPU{
   +Mainboard
   +Harddisk
   +Rom
   +Ram
}
class Equipment{
   +Power Supply
   +mouse
   +keyboard
   +loudspeaker
}
computer*-down- Equipment
computer*-down- CPU
@enduml
```
[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/NK_B2W8n4BlFLynPwJyiB88NOL7yW6hdKFgOscbP5l7VhTr5mTCa6HAIGOhEfGOFK6pnXAFN8YIeSEIGQg4CSFzeE4xN9o3Y_gHjlB7EfhDZ0yQAw-JCORqwm6lp7HxLfa2nhEw9PyfugIdvfGk1gr17ZfPVhkTg995shK6BsihibE4vgc_c_wELX86YQOlU)
 
