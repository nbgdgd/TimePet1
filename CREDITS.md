# Атрибуция графики и источников

Все питомцы — спрайт-атласы стандарта Codex-pet: 1536×1872, сетка 8×9,
ячейка 192×208, ряды idle / run-right / run-left / waving / jumping /
failed / waiting / running / review. Раскладка действий приложения по
кадрам — в `app/src/main/java/com/timeoverlay/pet/pet/PetDef.kt`.

## Mimi (по умолчанию)

- Файлы: `app/src/main/assets/pet/mimi/spritesheet.webp`, `pet.json`, `LICENSE`.
- Автор: **Jerry** — https://github.com/Spacebody/mimi-codex-pet
- Зеркало с метаданными: https://github.com/legeling/awesome-codex-pet/tree/main/pets/mimi--spacebody
  (`submission.json`: `"license": "MIT License"`); галерея — https://codexpet.top
  (та же коллекция, «Code under MIT · Pet assets under CC BY-NC 4.0» —
  общая пометка гелереи; у папки Mimi лицензия MIT указана явно).
- Лицензия: **MIT** (текст — `assets/pet/mimi/LICENSE`, Copyright (c) 2026 Jerry).
- sha256 атласа из зеркала: `f8acfb98b864a717a5876fc7a4ce696b2bced4998c62b913b4ddec30721760a0`
  (в `submission.json` указан другой хеш — зеркало прогоняет очистку краёв).

## Eigenblob (выбирается в настройках)

- Файлы: `app/src/main/assets/pet/eigenblob/spritesheet.webp`, `pet.json`.
- Источник: галерея codex-pet.com — https://codex-pet.com/pets/eigenblob
  (скачано 2026-09-15). Автор в галерее не указан.
- Лицензия: **на странице и в /docs не указана** (проверено 2026-09-15).
  Поэтому Eigenblob не выбран по умолчанию и годится только для личного
  некоммерческого использования с указанием источника; **перед публикацией
  в магазине** оставь Mimi или получи разрешение автора / галереи.

## Panda

- Файлы: `app/src/main/assets/pet/panda/spritesheet.webp`, `pet.json`, `LICENSE`.
- Автор: **Jason Bai** — https://github.com/Jason-Bai/pet
- Зеркало: https://github.com/legeling/awesome-codex-pet/tree/main/pets/panda--jason-bai
- Лицензия: **MIT** (LICENSE из репозитория автора, Copyright (c) 2026 Jason-Bai).
- sha256 атласа из зеркала: `a7c9d21f98af24566daa8fbbd67b65e6b48572eec885165d7b86c5a4311fb325`.

## Frankie

- Файлы: `app/src/main/assets/pet/frankie/spritesheet.webp`, `pet.json`, `LICENSE`.
- Автор: **Aygun Varol** — https://github.com/AygunVarol/Codex-Pet-Frankie
- Зеркало: https://github.com/legeling/awesome-codex-pet/tree/main/pets/frankie--aygunvarol
- Лицензия: **MIT** (LICENSE из репозитория автора, Copyright (c) 2026 Aygün).
- sha256 атласа из зеркала: `93d4bd6c9cb42ca7a18a71cbe2ee3587a2a8973f41a8d65e760f1328879e8aa1`.

## Wally

- Файлы: `app/src/main/assets/pet/wally/spritesheet.webp`, `pet.json`, `LICENSE`.
- Автор: **Wally Pet Contributors** — https://github.com/wally025/wally-codex-pet
- Зеркало: https://github.com/legeling/awesome-codex-pet/tree/main/pets/wally--wally025
- Лицензия: **MIT** (LICENSE из репозитория автора, Copyright (c) 2026 Wally Pet Contributors).
- sha256 атласа из зеркала: `f9b7d6dd1f9ab97f94d83b78b05f1246fc7c73b9c3c4678fd4ae314a41e25483`.

## Claude

- Файлы: `app/src/main/assets/pet/claude/spritesheet.webp`, `pet.json`, `LICENSE`.
- Автор: **XiangWang (xiangking)** — https://github.com/xiangking/Claude-style-Codex-pet
- Зеркало: https://github.com/legeling/awesome-codex-pet/tree/main/pets/claude--xiangking
  (https://codexpet.top/pets/claude--xiangking)
- Лицензия: **MIT** (LICENSE из репозитория автора, Copyright (c) 2026 XiangWang).
- sha256 атласа из зеркала: `ddab2df6b9f7c52267f6baad85d4c3a5ccceccae6ac1b0f325e97bb5348e0e75`.

## Frieren

- Файлы: `app/src/main/assets/pet/frieren/spritesheet.webp`, `pet.json`, `LICENSE`.
- Автор: **legeling** — https://github.com/legeling (фан-арт по «Фрирен, провожающая
  в последний путь»; `source_type: fan-art`, исходного репозитория нет).
- Зеркало: https://github.com/legeling/awesome-codex-pet/tree/main/pets/frieren--lingxiaotian
  (https://codexpet.top/pets/frieren--lingxiaotian)
- Лицензия: **CC BY-NC 4.0** — только некоммерческое использование с указанием
  автора. Права на персонажа принадлежат правообладателям (Kanehito Yamada,
  Tsukasa Abe). Поэтому Frieren открывается последней и не годится для
  платного распространения приложения.

У Panda, Frankie и Wally `submission.json` зеркала указывает `"license": "MIT License"`;
хеши в `submission.json` отличаются от файлов зеркала (зеркало прогоняет
очистку краёв), в `pet.json` записан хеш реально скачанного файла.

## Трейлер

- `TimePet-trailer.mp4` (RU) и `TimePet-trailer-en.mp4` (EN), 1080×1920, 24 с — чистая
  графика без записей экрана: `trailer/build_short.py ru|en` (PIL + ffmpeg), персонаж Claude.
- Музыка: **«Inspired» — Kevin MacLeod** (incompetech.com), лицензия
  **CC BY 4.0** (https://creativecommons.org/licenses/by/4.0/); файл
  `trailer/Inspired-KevinMacLeod-CCBY40.mp3`. При публикации указывать:
  «Inspired by Kevin MacLeod, incompetech.com, licensed under Creative Commons: By Attribution 4.0».
- Персонажи в трейлере — те же атласы, что в приложении (см. выше); в кадре
  есть Frieren (CC BY-NC), поэтому трейлер — только для некоммерческого показа.
- Шрифт подписей — Segoe UI (системный шрифт Windows, растрирован в кадры).

## Иконки

- Иконки интерфейса (`res/drawable/ic_*.xml`, кроме стрелок) - **Streamline
  Plump** (free set, стиль solid), автор Streamline, **CC BY 4.0**,
  https://www.streamlinehq.com/icons/plump ; получены через Iconify
  (https://api.iconify.design/streamline-plump:*.svg) и переведены в Android
  vector 1:1 (`viewportWidth 48`). Иконка запуска - та же лапа
  (`ic_launcher_foreground.xml`). Стрелки `ic_back`, `ic_chevron_right`,
  `ic_arrow_right` нарисованы вручную (три линии).
- Ранее пробовались Material Icons (Apache 2.0) и Solar Icons (CC BY 4.0) -
  заменены по просьбе заказчика (круглые подложки выглядели шаблонно).

## Рассмотренные и отклонённые варианты

- Tuantuan (jbbom, MIT) — второй кот, не добавлен ради разнообразия.
- Starcorn (alterhq, MIT) — единорог, есть грусть; не добавлен, чтобы не
  раздувать APK (каждый атлас ~1,5–2 МБ).
- Pixel Duck (Flamur Maliqi, CC BY 4.0) — один и тот же цикл во всех рядах,
  настроения не выразить. Diandian (MIT) и Yuanzai (MIT) — кадры почти
  одинаковые, состояния не читаются.
- Jesse the Fox, Serge le Lapin, Kiko, Night Neko и др. — только
  некоммерческие лицензии или лицензия не указана; не брались.
- Desk Otter (zihualiu1997, MIT) — выразительный, но «офисный работник»
  за столом плохо смотрится как питомец на телефоне; убран из сборки.
- Corgi Companion (cxian0928-afk, MIT) — всегда улыбается, грусть не выражена.
- Diandian (LLLucasXU, MIT) — кот с низкой детализацией.
- Pixel Duck (Flamur Maliqi, CC BY 4.0), Sunny Retriever (Legeling, CC BY-NC 4.0),
  Little Sheep (MingDong, CC BY-NC 4.0) — запасные варианты с явной лицензией.
- Фанатские персонажи галереи (Genshin, Naruto и т.п.) отклонены сознательно.
- Pixelify Sans (OFL) — пробовался для таймера, цифра «5» читается как «S»; заменён на VT323, а с 2.5 таймер - системным шрифтом.

## Каркас

- `base (2).apk` (пакет `com.timeoverlay`, TimeOverlay): публичный
  репозиторий не найден, лицензии нет, подпись debug. Декомпилированный код
  не копировался; переиспользованы только идеи (UsageStatsManager,
  инкрементальный опрос `queryEvents`, посуточные корзины).
  Тот же `applicationId`, чтобы сборка ставилась как обновление.

## Код приложения

Весь код в `app/src/main/java` написан для этого проекта и распространяется
под MIT (см. `LICENSE`).
