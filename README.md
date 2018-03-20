# Fallout 4 - Full Immersion
Сборка модов для полного погружения в игру с хардкорной составляющей.

> Моды подобраны 11.11.2017. Список перенесен в первоначальный репозиторий 20.03.2017 для наглядности.

> Я играю на режиме "Выживание". Да, с Loot Overhaul патроны на вес золота. Да, стимуляторы хрен найдешь, из-за чего зачистка любой локации это испытание. Да, я хожу со спальником, потому что ну вас нахер перепроходить последние 2 часа игры. Да, Arbitration причиняет боль пониже спины. Да, я не представляю шутер без смачных хед-шотов. И наконец, да, список не совершенен и еще много чего стоит подкорректировать, однако уже хорошо подходит для комфортной игры.


## Подготовка игры к установке модов

### Для установки ресурсных модов

1. Перейдите в папку C:\Users\Имя Пользователя\Documents\My Games\Fallout4 и откройте с помощью блокнота файл Fallout4Prefs.ini.
1. Найдите в этом файле конструкцию с заголовком `[Launcher]` и убедитесь, что в ней прописана строчка: `bEnableFileSelection=1` Если вдруг этой строчке нет, то впишите ее и сохраните файл.
1. Откройте блокнотом файл Fallout4.ini, который находится в этой же папке и найдите конструкцию с заголовком `[Archive]`.
1. В этой конструкции найдите строчку `sResourceDataDirsFinal=STRINGS\`.
1. Замените найденную строку на следующую:
`sResourceDataDirsFinal=STRINGS\, TEXTURES\, INTERFACE\, SOUND\, MUSIC\, VIDEO\, MESHES\, PROGRAMS\, MATERIALS\, LODSETTINGS\, VIS\, MISC\, SCRIPTS\, SHADERSFX\`
1. Сохраните изменения и закройте файл.

### Для установки плагинов ESP и ESM:

1. Использовать только Nexus Mod Manager.

------------------------------------------------------

<!-- 1. []() - -->

## Звук

1. [True 3D Sound for Headphones](https://rd.nexusmods.com/fallout4/mods/19680/?) - Создает эффект 3д в звуковом окружении. Теперь если, например, банка упала слева от игрока, то звук прозвучит отчетливо слева. *Теперь отчетливо понимаю на 2.1 колонках откуда стреляют.*

1. [Reverb and Ambiance Overhaul](https://rd.nexusmods.com/fallout4/mods/10189/?) - Улучшает общее игровое звучание, изменяет баланс некоторых звуков, делая общую картину более реалистичной, добавляет новые фоновые звуки. Теперь выстрелы в замкнутом и открытом пространстве будут координально различаться. *Наиболее лучший способ погрузиться в игру - это качественная обработка звука.*

1. [Radiant Birds](https://rd.nexusmods.com/fallout4/mods/2397/?) - Добавляет звуки птиц. *Вроде мелочь, но сильно влияет на погружение в одиночетво и безысходность*

1. [Towbie's Realistic Weapon Sounds](https://rd.nexusmods.com/fallout4/mods/130/?) - Изменяет "игрушечные" звуки выстрелов на более реалистичные и приятные. *Не представляю как я мог раньше играть без них. Пистолет 10-мм заиграл новыми красками.*

<!-- -------------------------------------- -->

## Графика

### Освещение

1. [Fr4nsson's Light Tweaks](https://rd.nexusmods.com/fallout4/mods/2139/?) - Улучшает освещение, делая его более реалистичным (на слабых системах даже поднимает фпс). Убирает [bloom](http://staticdelivery.nexusmods.com/mods/1151/images/2139-0-1448787312.gif) (гифка) - размытие, и [FakeLights](https://postimg.org/image/stvwfvh2b/) (гифка) - фейковые источники света, когда светло там, где источников света нет, особенно заметно в темных закрытых пространствах. *Так же не представляю, как раньше мог играть без него.*

1. [Darker Nights](https://rd.nexusmods.com/fallout4/mods/191/?) - Позволяет сделать нормальные настоящие темные ночи. Это вам не светлый Питер, это, бл, жуткий Бостон. *То, что доктор прописал.*

1. [True Storms - Wasteland Edition](https://rd.nexusmods.com/fallout4/mods/4472) - Полностью переделанная система штормов. Грозы, штормы, радиационные дожди. Новая уникальная погода, новые звуковые эффекты, эффекты частиц, текстуры и другое. *Отзыв: Двоякое впечатление. Как бы и круто, и атмосферно, но при этом кажется лишней и только просто так нагружает систему.*

1. [Extreme Particles Overhaul 2.0](https://rd.nexusmods.com/fallout4/mods/24159/?) - Добавляет красочные эффекты высокого разрешения для оружия. *Отзыв: определенно оставляю, новые эффекты выстрела лазерного мушкета буд-то добавляют "пушке" мощи.*

### Текстуры

1. [TOP + FAR (Заархированы в .ba2)](https://drive.google.com/open?id=19DNldJNDeNswtGViPNjvg2K2L524G6TC) - Готовые текстуры одних из лучших модов для оптимизации без потери качетва. Поднимает 10-15 фпс. Просто положить все файлы из "Repacked Archives" в "./Data" в корне игры.

<!-- ---------------------------------- -->

## Геймплей

1. [West Tek Tactical Optics](https://rd.nexusmods.com/fallout4/mods/12220/?) - Добавляет приборы ночного видения и тепловизоры, чтобы видеть в темноте и черные-черные ночи.

1. [Craftable Ammo](https://rd.nexusmods.com/fallout4/mods/798/?tab=description) - Позволяет игроку создавать патроны на хим. лаборатории. *Отзыв: must have, если бы не этот мод я бы давно уже умер, пусть и не на сложности "Выживание". Тем более патроны крафтятся не из говна и палок.*

1. [Arbitration](https://rd.nexusmods.com/fallout4/mods/2037/?) - Изменение боевой системы игры: ИИ старается держать игрока в поле зрения и не стост "столбом" по центу поля сражения; время ожидания до нападения снижено; коктейль Молотова при взрыве наносит меньше урона, но намного больше при самом горении; боле вероятны обходы врагов с фланга; радиус зрения большниства врагов увеличен в 2 раза, как и остальные показатели поиска игрока, что придает перкам большей значимости; увменьшен радиус действия компаса. *Отзыв: я всегда прохожу Станцию Оливия, когда проверяю механику боя, и сейчас было как-то сложнее и неоднозначней. Враги действовали намного агрессивней, чем обычно, учитывая, что я играю на стандартной сложности. И еше: сложилось впечатление без перков, что стелса в игре больше нет, я вообще ни к кому (вплотную так и подавно) не могу подкрасться.*

1. [Better Settlers](https://rd.nexusmods.com/fallout4/mods/4772/?) - Добавляет новые 240 вариаций сгенерированного поселенца с несколько уровней возможной классификации: от ношения разного оружия до военной брони.

1. [Ponytail Hairstyles by Azar v2.5a](https://rd.nexusmods.com/fallout4/mods/8126) - Добавляет 32 новых прически для девушек, но можно использовать и на мужчинах (-_^).

1. [Sim Settlements](https://rd.nexusmods.com/fallout4/mods/21872/?) - Теперь ваши поселения не нуждаются в постоянном присмотре и улучшении. Достаточно помогать поселенцам развиваться и они сами буду строить дома, фермы, магазины. Короче поселения на самообслуживании.

1. [Realistic Headshots](https://rd.nexusmods.com/fallout4/mods/2393/?tab=files) - При попадании в голове будет засчитан 20-кратный урон, кроме супер-крутых монстров, у которых по лору голова не самое слабое место. *Отзыв: Заставляет выцеливать голову противника, чтобы наверняка сразу убить (в лучше случае), иначе приходится долго возится.*

1. [Campsite - Simple Wasteland Camping](https://rd.nexusmods.com/fallout4/mods/11734/?) - Добавляет палатки, спальные мешки, кровати для собак, костры и фонари. *Отзыв: не разобрался в моде, ничего интуитивно понятного, снесу лучше.*

1. [Configurable Power Armor Fusion Core Drain](https://rd.nexusmods.com/fallout4/mods/325/?) - При установке позволяет изменить емкость ядра в Силовой Броне (я ставлю 25%). *Отзыв: Идеально для режима "Выживание", где без силовой брони первые 30 уровней не прожить.*

1. [Craftable Guns and Weapons](https://rd.nexusmods.com/fallout4/mods/1224/?) - Позволяет созадть абсолютно любое оружие в игре на оружейном верстаке.

1. [Loot Overhaul 2016 Edition](https://rd.nexusmods.com/fallout4/mods/1486/?) - Переделана система выпадения предметов вообще во всей игре. Теперь редкие вещи, которые в нынешнее время по канону нельзя произвести будут выпадать намного режеи и не в самых очевидных местах, в то время как вского хлама будет полно. Однако и в крутых военных кейсах теперь не будет желать всякое говно из трубок и палок. Цены у продавцов выросли в 2 раза, а цена продажи стала еще меньше; снижена вероятность нахождения легендарного снаряжения у побежденных особых противников; игрок не может больше собирать плоды с не-диких растений, для этого нужно использовать своих подопечных минитменов и тд. Теперь нельзя будет, поиграв 10 часов, нагибать все живое и разбрасываться стимуляторами. *Отзыв: за 4 часа игры я нашел 1 стимулятор с убитого врага. Однако вполне играбельно, тем более, что в редких ящиках я теперь не находил всякое говно, но и лута по мере игры очень мало. То есть за 8 часов игры я не смог найти медь для крафта генератора в поселении. Для "Выживания" не подходит, если ты не имбецил.*

1. [Faster Terminal Displays](https://rd.nexusmods.com/fallout4/mods/937/?) - Ускоряет отображение текста в терминалах. Советую выбирать х100.

<!-- ------------------------------------- -->

## Интерфейс (UI)

1. [HUDFramework](https://rd.nexusmods.com/fallout4/mods/20309/?) - UI-фреймворк (вспомогательный мод), который дает возможность другим модам изменять интерфейс игры.

1. [Full Dialogue Interface](https://rd.nexusmods.com/fallout4/mods/1235/?) - Нормальный интерфейс диалогов как в прошлых частях.

-------------------------------------

## Оптимизация

### Обязательные:

1. [Configuration Tool](https://rd.nexusmods.com/fallout4/mods/102/?) - Твикер (лежит .exe-файлом в ./Data), позволяющий настроить конфиги игры под себя, не копаясь текстовым редактором по самим файлам. Более подробная инструкция [ТУТ (пока нет)](#).

1. [ENBoost](http://enbdev.com/mod_fallout4_v0317.htm) - Позволяет установить лок на желаемый фпс, тк в конфиге отключается Вертикальная Синхронизация (V-Sync), фпс начинает "скакать" и игра становится нестабильное - то идет быстро, то в слоу-мо.
- Все файлы поместить в корневую папку игры.
- Открыть `enblocal.ini` текстовым редактором (блокнотом, как пример).
- Под тегом `[LIMITER]` включить лок на фпс `EnableFPSLimit=true` и указать предел `FPSLimit=59.0`.
- На клавишу звездочки на NumPad можно включить отображение фпс в игре.

1. [ShadowBoost](http://dev-c.com/files/ShadowBoost_1.9.4.0.zip) - Динамически урезает дальность прорисовки теней, чтобы поддерживать стабильный фпс, укзаный в конфиге.
- Все файлы поместить в корневую папку игры.
- Открыть `ShadowBoost.ini` текстовым редактором (блокнотом, как пример).
- `fTargetFramerate=56.0` - минимальный порог, до которого мод может позволить себе опустить фпс.
- `fShadowDrawDistMin=1000.0` - минимальная дистанция отрисовки теней.
- `fShadowDrawDistMax=13000.0` - максимальная дистанция отрисовки теней.
- 1000/3000/7000/14000 - минимальные/средние/высокие/ультра настройки дальности отрисовки теней в игре.

1. [Insignificant Object Remover](https://rd.nexusmods.com/fallout4/mods/9835/?) - Удаляет незначительные объекты для улучшения производительности без визуального ухудшения (мелкие камушки, которые, если не присматриватся, вообще незаметно).

### Для слабых систем:

1. [Wasteland 512 Textures Reloaded](https://rd.nexusmods.com/fallout4/mods/606/?tab=files) - Сильно-урезанные игровые текстуры, лучше всех улучшают производительность. *Качать: Wasteland 512 Textures Reloaded v2.2 - Package 9, Wasteland 512 Textures Reloaded v2.2 - Wasteland Workshop, Wasteland 512 Textures Reloaded v2.5 - Far Harbor.*

1. [Great FPS Boost](https://rd.nexusmods.com/fallout4/mods/5199/?) - Убирает туман на открытой местности, тени травы, еще больше урезает статичные тени - тем самым фиксит резкие просадки и фризы.

1. [Fog Remover](https://rd.nexusmods.com/fallout4/mods/275/?) - Убирает дым, туман в помещениях.

1. [Commonwealth Trash Removal Overhaul](https://rd.nexusmods.com/fallout4/mods/2711/?) - Убирает груды мусора, щебня и прочего говна, которое лишь только захламляет картинку и понижает производительность.

1. [Clean Settlement](https://rd.nexusmods.com/fallout4/mods/3100/?) - Убирает декоративную растительность, включая кустики в поселениях.
