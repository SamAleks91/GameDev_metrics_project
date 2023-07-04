Входные данные — файл attempts.csv, содержащий лог событий за
определенный промежуток времени по первым 500 уровням в игре.
Файл содержит четыре колонки:
uid — уникальный id игрока;
action — ‘completed’ для успешной попытки прохождения уровня, ‘failed’ для
неуспешной;
level — уровень, на котором произошло событие;
event_time — event_time/1000 является unix timestamp времени получения
события.
В рамках данного исследования была:
1) Предложены и рассчитаны метрики, описывающие сложность уровней;
2) Рассчитана "воронка" прохождения уровней новым пользователем после установки
игры.
_____________________________________________________________________________________________
The input data is a attempts.csv file that contains the event log for
time frame over the first 500 levels in the game.
The file contains four columns:
uid - player ID;
action - "completed" for the achievement of the result, "not completed" for the level
unsuccessful;
level - the level at which the event occurred;
event_time - event_time/1000 is the unix timestamp of getting the time
events.
As part of this study, it was:
1) Estimated and expected metrics describing hardness of levels;
2) Calculated "funnel" of new user levels after installation
of the game.
