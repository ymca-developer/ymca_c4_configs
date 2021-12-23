# YMCA_C4 configs
## EN
This repo is for example DayZ Standalone mod config files.

Config parameters:
* State - switch on/off raiding
* C4InitTime - time before explosion (seconds)
* C4Distance - radius of deletion (meters)
* C4DisarmTime - time mine takes to disarm (seconds)
* AvailiableTargets - array of constructions:
	* Target - construction typename
	* MaxHP - C4 count to destroy
	* RequiredAttachments - array of construction part names (check examples)
* WeekTimetable - array of day timetable:
	* Day - day of week (string)
	* StartH - start of work (hour)
	* StartM - start of work (minutes)
	* EndH  - end of work (hour)
	* EndM - end of work (minutes)
	Time must be 24h format Moscow local (UTC +3)

Typical config illustrating real-life settings based on vanilla fence is default_config.json.

There are some config files describing supported mod construction:
* moredoors https://steamcommunity.com/sharedfiles/filedetails/?id=2007175894
* simplebase https://steamcommunity.com/sharedfiles/filedetails/?id=1814422822
* basebuildingplus https://steamcommunity.com/sharedfiles/filedetails/?id=1710977250
* buildingfortification https://steamcommunity.com/sharedfiles/filedetails/?id=2670506982
* evenmoredoors https://steamcommunity.com/sharedfiles/filedetails/?id=2488972914

They consist of completely filled constructions. In the real configs you have to remove some of attachments and replace MaxHP param with your value.


## RU
Этот репозиторий преднозначен для примеров config файлов для мода на DayZ Stanalone.

Параметры config'а:
* State - включение/выключение рейда
* C4InitTime - время до взрыва (сек)
* C4Distance - радиус на котором удаляются постройки (метры)
* C4DisarmTime - время на разминирование (секунды)
* AvailiableTargets - список построек:
	* Target - typename постройки
	* MaxHP - количеста-во C4 для уничтожения
	* RequiredAttachments - список частей построек (см примеры)
* WeekTimetable - список расписаний на день
	* Day - день недели (строка на английском)
	* StartH - начало работы (час)
	* StartM - начало работы (минуты)
	* EndH  - конеч работы (час)
	* EndM - конеч работы (минуты)
	Время в 24-х часовом формате по Москве (UTC +3)

Типичный config, описывающий реальные настройки и основанный на ванильных воротах - default_config.json.

В репозитории представлены config файлы с описанием построек из поддерживаемых модов:
* moredoors https://steamcommunity.com/sharedfiles/filedetails/?id=2007175894
* simplebase https://steamcommunity.com/sharedfiles/filedetails/?id=1814422822
* basebuildingplus https://steamcommunity.com/sharedfiles/filedetails/?id=1710977250
* buildingfortification https://steamcommunity.com/sharedfiles/filedetails/?id=2670506982
* evenmoredoors https://steamcommunity.com/sharedfiles/filedetails/?id=2488972914

Они содержат полностью заполненные частями постройки в AvailiableTargets. В реальных конфигах необходимо удалить ненужные части и поменять значение MaxHP на свое.