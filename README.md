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
 
* รูปที่ 2 Car
```
@startuml

title Classes - Car

car*-down- mirror
car o-down- wheel
car o-down- engine
car*-down- door
car*-down- steeringwheel 
@enduml
```
[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/LSrB2e0m38JXVKwHjT0x57gIOWSjr1IIYDVt3RgS3tucccVrTMb4Nhs1KyjcC0wSiXADMOTG-YQ1bwhQzHJk3sqpq7u2cQhWcvL-H-ys1xJATBLC4LAE-nq0)
