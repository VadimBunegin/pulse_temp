# pulse_temp


https://docs.google.com/document/d/18JuiLkYVevIXZ3uAHhflQMRPbNuUw4L3ph_Ykb2jbhA/edit?usp=sharing
Внедрение информационных систем стало необходимым условием повышения эффективности систем охраны и мониторинга здоровья человека. Сегодня главными критериями качества получаемой информации являются точность и достоверность. К сожалению, многие производители различных медицинских приспособлений и технологий, за счет удешевления и минимизации затрачиваемых на разработку усилий, сильно пренебрегают описанными выше критериями. 

Целью работы является повышение эффективности отслеживаемой информации датчика сердечного ритма и термометра посредством внедрения информационных технологий, электронных компонентов, системы контроля версии git, платы NodeMCU и протокола MQTT.

Достижение поставленной цели требует решения ряда задач. 
Изучить теоретические аспекты информационных технологий, программирования на Arduino, написания web-приложений на Django (Python), использование баз данных SQL, принципы работы датчика сердечного ритма (Pulse sensor) и системы контроля версии git. 
Сформулировать необходимость использования информационных технологий для мониторинга жизненных показателей.
Разработать проект по повышению точности информации посредствам внедрения IT-технологий

Практическая значимость исследования обусловлена возможностью использования данного проекта для автоматизированного отслеживания человеческих показателей.

Практическая часть
1) Датчик сердечных сокращений, считывает и передает импульсы тока на микроконтроллер. 
2) NodeMCU считает импульсы. 
3) Микроконтроллер через сеть WI-FI посредствам GET-запроса передает показания на сервер web-приложения, написанного на Django.
4) Данные записываются в SQLite, с помощью языка Python и фреймворка pandas для него.

схема подключения:
![telegram-cloud-photo-size-2-5377629204889323143-y](https://github.com/VadimBunegin/pulse_temp/assets/61832909/26369027-7bcc-4f15-a476-cea0a3f637b8)
