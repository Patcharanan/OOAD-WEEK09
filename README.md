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


* รูปที่ 3 Rent Car
```
@startuml

title Classes - Class RentCar
left to right direction
class Customer{
   -Cust_id
   #Lastname
   -Firstname
   -Address
   -Postal_Code
}
class Rent{
   -Rent_ID
   -Cust_ID
   -Reg_No
   #Rent_Date
   #Return_Date
}
class Car{
   -Reg_No
   #Model_ID
   #Rate
}
class CarType{
   -Model_ID
   +Mark
   +Model
   +Year
}
Customer -- Rent
Rent -- Car
Car -- CarType
@enduml
```
[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/NP31YW8n38RlUOg0HvbtK4OM5dIHmSkUXcApMhRJIfevB8FlRjDMLZoqV7-R_6d_JHB3CayUG9numjwRb2XXLma72j8R1ay_WXAHtUKgQ1tJMLmCS2vL_PmaJiGB86AdQdHMURKtIOAPg5nyE7vHMskPKYfyZFaXVkoZ9RWtKnrT3PN6pzs_UUE1BkDNB7DAoSu8DIKpXwgVTlaNotlN8S_ppMqrl5MV_cvKErxBrWV3lnNqjD0tvOJky4m1kwuy7dHJeG7crL1zOKF1vjWV)


* รูปที่ 4 Speed Enforcer
```
@startuml

title Classes - Class Speed Enforcer
left to right direction
class SpeedEnforcer{
   +CourtLocation
   +date
   +calculateSpeed()
}
class Car{
   +modelType
   +Doors
   +autoMaker
   -Radio()
   +windshieldWiper()
   +changeDirection()
}
SpeedEnforcer --> Car
@enduml
```
[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/LL112i8m4Bpd5NjKf5-GGkjDBofuNf9j6upPacmG4VzkchQ8jvdTcPrXwoWO93sSKcB54JGEOwG8rOpWCX8PEFYEWwQW77K2mX1iFmWO6qYBPQ_qJxngtme0TWsd84VMM6JJnA1G0HgTJYwpOjjirMSvq-1YVh0XTtsDixvb3h4WJC8dlES-cLLdD9QpVTeyhJTniEJCpOuKbgaUqFVKhcrBr5zNgAhz5AjgyYP_umi0)
