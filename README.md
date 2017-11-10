# Fallout 4 - Full Immersion
Сборка модов для полного погружения в игру с хардкорной составляющей.

*Подробная устанока мода описана в отдельном readme каждого мода*

## Подготовка игры к установке модов

### Для установки ресурсных модов

1. Перейдите в папку C:\Users\Имя Пользователя\Documents\My Games\Fallout4 и откройте с помощью блокнота файл Fallout4Prefs.ini.
1. Найдите в этом файле конструкцию с заголовком `[Launcher]` и убедитесь, что в ней прописана строчка: `bEnableFileSelection=1` Если вдруг этой строчке нет, то впишите ее и сохраните файл.
1. Откройте блокнотом файл Fallout4.ini, который находится в этой же папке и найдите конструкцию с заголовком `[Archive]`.
1. В этой конструкции найдите строчку `sResourceDataDirsFinal=STRINGS\`.
1. Замените найденную строку на следующую:
`sResourceDataDirsFinal=STRINGS\, TEXTURES\, INTERFACE\, SOUND\, MUSIC\, VIDEO\, MESHES\, PROGRAMS\, MATERIALS\, LODSETTINGS\, VIS\, MISC\, SCRIPTS\, SHADERSFX\`
1. Сохраните изменения и закройте файл.

### Для установки плагинов ESP и ESM используйте NMM (авто) или вручную:

1. Найдите файл plugins.txt, находящийся по адресу C:\Users\Имя Пользователя\AppData\Local\Fallout4.
1. Кликните по файлу правой кнопкой мыши и выберите пункт «Свойства».
1. Уберите галочку с пункта «Только чтение» и нажмите кнопку «Применить».
1. Откройте файл блокнотом и сразу после строчки Fallout4.esm, вставьте полное название скачанного мода с расширением (например, `ReverbandAmbianceOverhaul.esp`).
1. Сохраните и закройте файл.
1. Установите файлу свойство "Только чтение".

------------------------------------------------------

<!-- 1. []() - -->

## Звук

1. [True 3D Sound for Headphones](https://rd.nexusmods.com/fallout4/mods/19680/?) - Создает эффект 3д в звуковом окружении. Теперь если, например, банка упала слева от игрока, то звук прозвучит отчетливо слева. *Теперь отчетливо понимаю на 2.1 колонках откуда стреляеют.*

1. [Reverb and Ambiance Overhaul](https://rd.nexusmods.com/fallout4/mods/10189/?) - Улучшает общее игровое звучание, изменяет баланс некоторых звуков, делая общую картину более реалистичной, добавляет новые фоновые звуки. Теперь выстрелы в замкнутом и открытом пространстве будут координально различаться. *Наиболее лучший способ погрузиться в игру - это качественная обработка звука.*

1. [Radiant Birds](https://rd.nexusmods.com/fallout4/mods/2397/?) - Добавляет звуки птиц. *Отзыв: сделано добротно, определенно оставить.*

1. [Towbie's Realistic Weapon Sounds](https://rd.nexusmods.com/fallout4/mods/130/?) - Изменяет "игрушечные" звуки выстрелов на более реалистичные и приятные. *Не представляю как я мог раньше играть без них. Пистолет 10-мм заиграл новыми красками.*

## Графика

### Освещение

1. [Darker Nights](https://rd.nexusmods.com/fallout4/mods/191/?) - Позволяет сделать нормальные настоящие темные ночи. Это вам не светлый Питер, это, бл, жуткий Бостон. *То, что доктор прописал.*

1. [True Storms - Wasteland Edition](https://rd.nexusmods.com/fallout4/mods/4472) - Полностью переделанная система штормов. Грозы, штормы, радиационные дожди. Новая уникальная погода, новые звуковые эффекты, эффекты частиц, текстуры и другое. *Отзыв: Двоякое впечатление. Как бы и круто, и атмосферно, но при этом кажется лишней и только просто так нагружает систему.*

1. [Extreme Particles Overhaul 2.0](https://rd.nexusmods.com/fallout4/mods/24159/?) - Добавляет красочные эффекты высокого разрешения для оружия. *Отзыв: определенно оставляю, новые эффекты выстрела лазерного мушкета будто добавляют "пушке" мощи.*

## Геймплей

1. [West Tek Tactical Optics](https://rd.nexusmods.com/fallout4/mods/12220/?) - Добавляет приборы ночного видения и тепловизоры, чтобы видеть в темноте и черные-черные ночи.

1. [Craftable Ammo](https://rd.nexusmods.com/fallout4/mods/798/?tab=description) - Позволяет игроку создавать патроны на хим. лаборатории.

1. [Arbitration](https://rd.nexusmods.com/fallout4/mods/2037/?) - Изменение боевой системы игры: ИИ старается держать игрока в поле зрения и не стост "столбом" по центу поля сражения; время ожидания до нападения снижено; коктейль Молотова при взрыве наносит меньше урона, но намного больше при самом горении; боле вероятны обходы врагов с фланга; радиус зрения большниства врагов увеличен в 2 раза, как и остальные показатели поиска игрока, что придает перкам большей значимости; увменьшен радиус действия компаса. *Отзыв: я всегда прохожу Станцию Оливия, когда проверяю механику боя, и сейчас было как-то сложнее и неоднозначней. Враги действовали намного агрессивней, чем обычно, учитывая, что я играю на стандартной сложности.*
