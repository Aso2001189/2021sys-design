```uml
@startuml
:天気情報 ←　weather;

if(weather = 0)
:快晴です;
elseif(weather = 1)
:曇りです;
else
:不明です;
endif

stop
@enduml
```
