```uml
@startuml
start
:天気情報 ←　weather;

if(weather = 0) then(はい)
:快晴です;
else(いいえ）
elseif(weather = 1) 
:曇りです;
elseif(weather = 2) 
:雨です;
else 
:不明です;
endif

stop
@enduml
```
