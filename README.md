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
1. Откройте файл блокнотом и сразу после строчки Fallout4.esm, вставьте полное название скачанного мода с расширением (например, `Reverb and Ambiance Overhaul.esp`).
1. Сохраните и закройте файл.
1. Установите файлу свойство "Только чтение".

------------------------------------------------------

## Звук

<!-- 1. []() - [Установка]() - -->

1. [True 3D Sound for Headphones](https://rd.nexusmods.com/fallout4/mods/19680/?) - [Установка](https://github.com/lomeat/full-immersion/tree/master/True%203D%20Sound%20for%20Headphones) - Создает эффект 3д в звуковом окружении. Теперь если, например, банка упала слева от игрока, то звук прозвучит отчетливо слева.

1. [Reverb and Ambiance Overhaul](https://rd.nexusmods.com/fallout4/mods/10189/?) - [Установка](https://github.com/lomeat/full-immersion/tree/master/Reverb%20and%20Ambiance%20Overhaul%20-%20ALL%20DLC) - Улучшает общее игровое звучание, изменяет баланс некоторых звуков, делая общую картину более реалистичной. Теперь звуки выстрелов в замкнутом и открытом пространстве будут координально различаться.

1. [Radiant Birds](https://rd.nexusmods.com/fallout4/mods/2397/?) - [Установка](https://github.com/lomeat/full-immersion/tree/master/Radiant%20Birds%20v0.5) - Добавляет звуки птиц.

1. [Towbie's Realistic Weapon Sounds](https://rd.nexusmods.com/fallout4/mods/130/?) - [Установка](https://github.com/lomeat/full-immersion/tree/master/Towbie's%20Realistic%20Firearms) - Изменяет "игрушечные" звуки выстрелов на более реалистичные и приятные.

## Графика, освещение, окружение

1. [Darker Nights](https://rd.nexusmods.com/fallout4/mods/191/?) - [Установка](https://github.com/lomeat/full-immersion/tree/master/Darker%20Nights) - Позволяет сделать нормальные настоящие темные ночи. Это вам не светлый Питер, это, бл, жуткий Бостон.

1. [West Tek Tactical Optics](https://rd.nexusmods.com/fallout4/mods/12220/?) - [Установка](https://github.com/lomeat/full-immersion/tree/master/West%20Tek%20Tactical%20Optics%20v2.0.1) - Добавляет приборы ночного видения и прочую шелоху, чтобы видеть в эти черные-черные ночи.

1. [Extreme Particles Overhaul 2.0](https://rd.nexusmods.com/fallout4/mods/24159/?) - [Установка]() - Добавляет красочные эффекты высокого разрешения для оружия.
