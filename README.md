# script-to-SPTSclassic

Команды
Основные команды
help          # Список всех команд
stats         # Открыть статистику
ts            # Начать отслеживание прогресса
tss           # Остановить отслеживание
tsg           # Открыть панель прогресса
wiki          # Открыть вики
clear         # Очистить вывод консоли
ESP команды
esp on        # Включить ESP
esp off       # Выключить ESP  
esp toggle    # Переключить ESP
players       # Список игроков онлайн
tp @Имя       # Телепорт к игроку
Fist Training
fs on         # Включить автофарм силы
fs off        # Выключить автофарм силы
rock          # Телепорт на The Rock
crystal       # Телепорт на The Crystal
bluegod       # Телепорт на Blue God Star
greengod      # Телепорт на Green God Star
redgod        # Телепорт на Red God Star

Структура проект
├── main.lua                 # Главный загрузчик
├── Utility.lua              # Утилиты и хелперы
├── Systems/
│   ├── StatsSystem.lua      # Система статистики
│   ├── ProgressSystem.lua   # Трекер прогресса
│   ├── ESPSystem.lua        # ESP и телепортация
│   ├── WikiSystem.lua       # База знаний
│   ├── CommandConsole.lua   # Консоль команд
│   └── AutoFarmSystems.lua  # Автофарм системы
└── Data/
    ├── WikiData.lua         # Данные вики
    └── Locations.lua        # Координаты локаций
