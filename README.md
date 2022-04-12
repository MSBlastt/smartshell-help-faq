# Ответы на наиболее часто задаваемые вопросы по работе с SmartShell

Канал SmartShell в Telegram: https://t.me/smartshellgg  
Чат взаимопощи: https://t.me/+ToRYZbfOlNdlMDQy

Полезный ролик по первичной настройке системы: https://youtu.be/DcRhKccPvcA

### Какая актуальная версия SmartShell?
0.6.5.3 сервер. 0.6.5.2 клиент (шелл)

### Не работает автозапуск игр в стиме? Как настроить?
На примере CS:GO

![image](https://user-images.githubusercontent.com/10057097/160152535-ea193f93-39e9-40bf-a6e3-facc00765672.png)

### Работает ли SmartShell на бездиске (напр. ccboot)
Работает. Автор текста лично установил, всё ок. Есть нюансы с регистрацией станций. Нет прямого ввода мак адреса (как в сенете). Нужно вручную на каждом хосте после подключения указать корректное имя ПК. Через Ctrl+alt+p -> редактировать параметры и указать адрес сервера.

### Как обновить локальный сервер?
Вам пришлют инструкцию в личный чат с вашим клубом. В техподдержке просили отправить в ваш чат сообщение с тегом #localss, чтоб вас быстрее нашли.
UPD: судя по отзывам обновлять локальный сервер лучше при отключенном шелле на всех ПК, иначе чревато проблемами

### Как обновить облачный сервер?
Это произойдёт автоматически. Возможны перебои в работе сервера на 3-5-10 и более минут (сервер будет отдавать 502 ошибку).

### Как обновить клиентский шелл?
Автоматически при загрузке шелла. Возможно, необходимо перезагрузить компьютер несколько раз для полного обновления.

### Как загрузить базу юзеров из Senet/SmartShell завис при загрузке базы.
Многие отмечали, что базу лучше не загружать. Есть проблемы с форматом выгружаемых из сенета данных. Пароли не переносятся. Их придётся восстанавливать в любом случае.

### Как работать с кассой? Как печатать чеки? Есть ли интеграция?
Интеграции сейчас нет. Обещают, но не очень скоро. Если у вас не автономоная касса (аля Эватор), а, например, Штрих Онлайн. То нужен сторонний софт. Можно взять Контур Маркет. https://kontur.ru/market . Настроить связь с кассой поможет техподдержка контура, можно бить чеки на произвольную сумму и печатать отчёты.

### Как бронировать? Где модуль бронирования?
Его пока нет. Реализацию обещают. Пока можно воспользоваться этим - https://restoplace.cc/ 

### Как мониторить и управлять консолями? Можно как-нибудь переиспользовать сенетовские контроллеры?
Пока, увы, никак. Можно завести виртуальный хост (добавить как отдельный пк в дашборд) - и вести учет там - над коробочкой уже работают.

### Не приходят смс-ки\нет звонка с подтверждающим кодом при регистрации
Начиная с 24 марта смски больше не будут приходить. только подтверждающий звонок. В поле подтверждения нужно ввести последние 4 цифры входящего номера. В интерфейсе пока старое упоминание о смске, будет исправлено со следующей версией. Также (на данный момент) сервис смсок и звонков периодически отваливается. Тем кто ещё не обновил локальный сервер, но обновил шелл, пока никто не позвонит. Есть временный лайфхак: вводите данные клиента -> регистрация -> поле с кодом оставляете пустое -> подтвердить. Выдаст ошибку якобы кода нет, но клиент на самом деле добавится в базу. Можно логиниться и покупать тариф.

 ### Как пересадить клиента за другой комп?
 У оператора, правой кнопкой по компьютеру - пересадить/
 
 ### Как выйти из шелла в виндовс?
 Нажать ctrl+alt+p (убедитесь, что выбрана английская EN раскладка), далее вводите пароль. Если не меняли, то пароль pasw0rd (одна буква s, после w ноль)
 
 ### Как открыть диспетчер задач?
 Без танцев с бубном пока никак. Очень скоро добавят в шелл. Можно временно поставить как отдельное приложение что-то типа ProcessKiller 
 
 ### Сбивается время при поминутной тарификации/автоматически не переключается на поминутную тарификацию после окончания пакета/фиксированного тарифа
 С поминутной тарификацией пока есть проблемы. В версии 0.6.5.0 должны устранить. Пока можно пользоваться только фиксированными тарифами (15, 30, 45 мин, 1, 3, 5 часов)
 
 ### Почему некоторые игры не отображаются в шелле? Хотя добавлены в приложения под менеджером?
 При инициализации шелл пробегает по всем файлам (путям к файлам) для добавленных игр. И если не находит, то не будет отображать. Если пути отличаются на разных ПК для одной и той же игры, то можно добавить до 3х путей к игре в админке.
 
 ### Как сделать несгораемый пакет?
 Пока никак. Скоро исправят. Более того при разлогине у клиента полностью сгорит весь остаток. Будьте внимательны, если нужно пересадить клиента см. выше как
 
 ### Как добавить настройки громкости/микрофона в Шелл?
 Для этого есть отдельные приложения C:\Windows\System\Smartshell\MouseUtil.exe и SoundUtil.exe, чтобы клиенты смогли настраивать мышь и звук
Добавьте их в программы. Либо добавляйте фирменные утилиты от производителя мышки (Logitech, SteelSeries...).
 
 ### Черный экран при входе в игру или шелл. Компьютер постоянно перезагружается после запуска.
 Скорее всего проблема связана с неполным и\или некорректным удалением остатков сенета. Из лайфхаков советовали открыть предварительно проводник и вычистить файл hosts от левых адресов которые остались после сенета. Если на операционке раньше стоял сенет, то рекомендуется снести ОС и на свежий дистрибутив устанавливать SmartShell. Техподдержка смартшелла рекомендует запустить следующий .bat файл с фиксом
 
```sc stop shellsystemsvc
powershell.exe -Command Invoke-WebRequest "https://dl.smartshell.gg/sshellsvc0500.zip" -OutFile "ssusvc.zip" -UseBasicParsing
powershell.exe -Command Expand-Archive -Path ssusvc.zip -DestinationPath C:\ProgramData\ssusvc\ -Force
sc start shellsystemsvc
pause
```

UPD: **Из чата. Только что нашли основную причину вылета шелла в черный экран. 90% случаев связаны с тем, Что к компьютеру не подключены наушники**
 
 ### В чем отличие в кассовом отчёте: покупки за смену и выручка за смену
Покупки = (нал + безнал + депозит)
Выручка = (нал + безнал)
оплата налом и картой - внесение денег клубу
депозит - просто трата части уже внесенных денег, не входит в выручку

### Чем депозит от оплаты отличается в смысле кассы?
Чтобы понимать, сколько людей сидят под зарегистрированными аккаунтами, а кто под гостевыми
 
 ### Все игры нормально работают в SmartShell?
 Подтверждались проблемы с Escape From Tarkov, Warzone и Valorant
 
 ### Есть ли готовый набор подходящих картинок для карточек в SmartShell?
 Добрые люди поделились
 https://drive.google.com/drive/folders/1bPNTUB4W2VmZ9E2X6nnT2mjwGWW9oSsm
 
 ### Не работает alt+tab переключение. Как альтабнутся из игры?
 Пока только через win+d (сворачивание окон). ВНИМАНИЕ! С этим методом есть нюанс, что не во все игры можно будет вернуться обратно, предупреждайте клиентов.  Обещают пофиксить в версии 0.6.5.0

UPD: Игры запущенные в окне без рамки сворачиваются и разворачиваются нормально. Для CS:GO в аргументах командной строки можно прописать -high -noborder, альт+таб работает в обе стороны. Дота с такими же параметрами альт+табом не сворачивается, но можно нажать Win+D, разворачивается альт+табом нормально.
UPD2: Важное уточнение: если путь к игре в стиме прописан сразу в таком формате steam://rungameid/730, в таком случае аргументы командной строки не работают. У меня во всяком случае CS:GO запускалась без параметров, пока не переписал путь.
 
 ### Как посадить клиента без регистрации/аккаунта?
 Оператор может просто продать тариф на компьютер. Начнётся гостевая сессия. С дашборда под оператором, правой кнопкой по ПК -> назначить тариф.
 
 ### После перезагрузки надо вводить пароль от винды, чтобы открылся рабочий стол/шелл
 Используйте программу SmartShell AutoLogon из инструкции. Необходимо, чтоб у виндового пользователя был хоть какой-нибудь (не пустой) пароль.
 Также предлагали такой вариант:
![image](https://user-images.githubusercontent.com/10057097/160170554-561865eb-2171-4322-a313-127507e985f5.png)

 
 ### Как войти в админ панель с любого ПК (внутри сети) если сервер локальный?
Из инструкции

![image](https://user-images.githubusercontent.com/10057097/160271012-f964caca-9303-4b5e-9867-b3e277d8ed0b.png)
 
 ### Как удалить сотрудника?
 Пока что нет такой возможности. Только блокировка. Совсем скоро добавят.
 
  ### Как сбрасывать стим акки при выходе с сессии?
 Скоро добавят автовыход из всего после перезагрузки. Как вариант создайте аккаунт «пустышку» и сделайте так чтобы при открытии стима всегда логинился этот самый аккаунт. В параметрах запуска стима пропишите «-login login password» без скобок и он будет пытаться залогинить не существующую связку при каждом запуске. Костыль, да. Но решит вашу проблему точно
 
 ### Проблема при пополнении депозита на аккаунт пользователя, он играет в данный момент у него заканчивается баланс ему нужно пополнить депозит и выходит ошибка. Как быть?
 Такая беда есть. Обещали фикс запилить.
 
 ### Как добавить софт для мышек HyperX (HyperX NGenuity)
 Ищите в чате взаимопощи установочный файл который не требует привязки к Windows Store.
 
 ![image](https://user-images.githubusercontent.com/10057097/162964606-cf295f16-1e26-44fc-bbbc-7d591d797b28.png)

 
 ### Как настроить запуск игры CS 1.6?
Стим
Путь: D:\Games\Steam\steam.exe
Аргумент: -applaunch 10 -no-friends -no-browser

Пиратка
Работоспособность зависит от сборки. Путь нужно прописать до батника, не до hl.exe
 
 ### Как добавить дискорд?
 ![image](https://user-images.githubusercontent.com/10057097/160169832-7a4b1dad-6956-40cd-a3b0-34c0c76fd225.png)

 ### Как добавить программу из Windows Store? Например софт для HyperX?
 https://comp-security.net/запуск-приложений-из-microsoft-store-через-cmd/
 или Через планировщик задач настройте на запуск
 или после установки пропишите путь к .lnk ярлыку на рабочем столе
 
 ### Как добавить игру Х?
 В чате проскакивала такая простыня:
 
 ```#Riot Games: Runtera 
"ПутьДоРиот/RiotClientServices.exe" параметры запуска: --launch-product=bacon --launch-patchline=live
#Riot Games: Lol
ПутьДоРиот/RiotClientServices.exe" параметры запуска: --launch-product=league_of_legends --launch-patchline=live
#Riot Games: Valorant
ПутьДоРиот/RiotClientServices.exe" параметры запуска: --launch-product=valorant --launch-patchline=live
#Epic Games (Fortnite)
Можете просто зайти в эпик и там создать ярлык и из него вытащить данные. Наглядно будет примерно как-то так:
Epic: com.epicgames.launcher://apps/GAMEID?action=launch
Что было у нас в ярлыке:
com.epicgames.launcher://apps/fn%3A4fe75bbc5a674f4f9b356b5c90567da5%3AFortnite?action=launch&silent=true 
Также вы можете поступить совершенно с любой игрой в epic games
#Steam
Просто можете использовать вот такую подпись в карточке
"steam://rungameid/GAMEID (GameId - айди игры на платформе Steam)
Если не появляется карточка в шелл так, то пропишите пусть до стима  и в параметрах запуска "-applaunch айди игры"
На данном сайте https://steamdb.info/apps/  можно узнать айди всех игр из стим по названию.
#Battle.net 
Пока нет параметров запуска просто путь до игры, однако
У Heartstone нужно прописать путь до Hearthstone Beta Launcher.exe, потому что, если вы запустите Hearstone.exe запустится сама игра, а если пользователь еще не залогинен в лаунчере, то будет бесконечно грузиться.
#Origin
Используйте такую подпись в карточке: 
1: origin://launchgame/GAMEID 
2: origin://launchgamejump/GAMEID
3: origin2://game/launch/?offerIds=GAMEID
GAMEID - это уникальный айди каждой игры на платформе Origin 
Чтобы узнать правильный GAMEID для игры Origin:*
Войдите на сайт https://www.origin.com с вашей учетной записью origin > Выберите "Библиотека" и игру.
Идентификатор игры является частью URL-адреса в вашем браузере.
#Uplay 
Используйте такую подпись в карточке: 
uplay://launch/GAMEID
GAMEID - это уникальный айди каждой игры на платформе Uplay
узнать правильный GAMEID для Uplay:
Создайте ярлык игры на рабочем столе > Щелкните правой кнопкой мыши меню Свойства > Скопируйте путь игры вида "uplay://launch/GAMEID" > Вставьте в карточку```

### Где в директории smartshell находится вся база данных? Чтобы настройки smartshell не терялись при переустановке.
База в backend/docker/databases/postgres
ключи в backend\storage
и .env обязательно сохраните
Пароли шифруются bcrypt'ом по ключам в папке storage
```

### Батник на удаление майнера от сенет типа wusvcs.bat (остатки от сенета если не переустановили ОС)
Он маскируется под параметры системы. Также там бонусом закрытие протов на пк на которые могут закинуть вирус скрипты, и удаленное управление системой винды(Именно удал раб стол от Windows)


```@echo off
echo Zakryvaem porty...

TIMEOUT /t 3 /NOBREAK

echo Farmim premogemy v gen^in...

TIMEOUT /t 1 /NOBREAK

echo Vyhodim posmoukat'...

TIMEOUT /t 1 /NOBREAK

echo Inicializaci^ processa
 
netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=135 name=“Block1_TCP-135”

netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=137 name=“Block1_TCP-137”

netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=138 name=“Block1_TCP-138”

netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=139 name=“Block_TCP-139”

netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=445 name=“Block_TCP-445”

netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=5000 name=“Block_TCP-5000”

netsh advfirewall firewall add rule dir=in action=block protocol=tcp localport=8888 name=“Block_TCP-8888"

echo Porty zakryty! 

echo Zapuskaem udalenie majnera...

TIMEOUT /T 5 /NOBREAK

echo Inicializaci^...

TIMEOUT /T 2 /NOBREAK

taskkill /IM Client.exe /T /f

taskkill /IM wusvcs.exe /T /f

cs delete wusvcs

del /f c:\Windows\Client.exe

del /f c:\Windows\System32\wusvcs.exe 

echo Udalenie zaver^enno 

TIMEOUT /T 2 /NOBREAK

echo done
echo Click any button to exit
pause

 end
 ```
 
 ### Очистка файлов виндоус, которые захламляют систему (остатки от сенета если не переустановили ОС)
 ```@echo off
del /s/q/f  C:\Users\support\AppData\Local\Temp\*
del /s/q/f  C:\Users\user\AppData\Local\Temp\*
del /s/q/f C:\Windows\SoftwareDistribution\Download\*
del /s/q/f C:\Windows\prefetch\*
del /s/q/f E:\Steam\steamapps\workshop\*
del /s/q/f C:\Users\support\Downloads\*
del /s/q/f C:\Users\user\Downloads\*
del /s/q/f C:\Users\support\AppData\Roaming\.minecraft\logs\*
exit
```
