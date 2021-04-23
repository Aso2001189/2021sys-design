```uml
@startuml
start
:天気情報 ←　weather;

if(weather)then(0)
:快晴です;
else then(1)
:曇りです;
else 
:不明です;
endif

stop
@enduml
```
