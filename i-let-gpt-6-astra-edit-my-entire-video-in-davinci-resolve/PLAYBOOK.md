# I Let GPT-6 Astra Edit My Entire Video in DaVinci Resolve!

**Video:** https://www.youtube.com/watch?v=kOoC3yhUyDQ
**Published:** 2026-10-02
**Duration:** 11:37
**Channel:** Higgsfield AI
**Article:** https://higgsfield.ai/@adilinthewildtempo/blogs/faster-video-editing-with-astra-higgsfield
**Install MCP (description short link):** https://higgsfield.ai/s/astra-for-editing-higgsfieldai-HQLlcE
**Skill + SFX (description short link):** https://higgsfield.ai/s/astra-for-editing-higgsfieldai-XqLQyi
**ChatGPT plugin:** https://higgsfield.ai/mcp?tab=chatgpt
**MCP URL:** https://mcp.higgsfield.ai/mcp
**Resolve plugin (separate panel, not this skill):** https://higgsfield.ai/plugins/davinci

Article by @adilinthewildtempo, dated 2026-10-02. It ships two downloads and no Recreate boxes. The skill zip is `YT_video_editor_skill_2026-09-22.zip`. Inside it the folder is `yt-video-editor-skill`. The sound zip is `Sound Library.zip` (227 audio files). Do not re-host either zip.

## Final Result

A finished edit driven by GPT-6 Astra inside DaVinci Resolve, plus After Effects for motion graphics. The video builds four jobs:

1. A commercial titled "Editing Has Changed". Generate footage, cut it, add sound, set pacing.
2. A rebuilt YouTube video from existing material, with screen recordings synced to B-roll.
3. A color grade in DaVinci Resolve.
4. Motion graphics in After Effects, then a long-form cut turned into Shorts.

Chapters on the watch page:

- 0:00 Can AI edit videos?
- 0:56 Creating the "Editing Has Changed" commercial
- 3:09 Refining the edit, sound design, and pacing
- 4:50 Rebuilding a YouTube video with Astra
- 6:04 Color grading in DaVinci Resolve
- 6:23 Syncing screen recordings and B-roll
- 6:46 Motion graphics in Adobe After Effects
- 8:05 Turning long-form videos into Shorts

The shipped skill is Max's personal YouTube edit process, written in Russian. Display name: `YT_video_editor_skill`. It does not generate Seedance prompts. It tells the agent how to assemble a cut in Resolve: stringout by script, A/B/C cameras, screencasts, short on-frame briefs, motion notes, and a check before delivery.

## Skill Installation

### A. Higgsfield in GPT-6 Astra

1. Open the description install link: https://higgsfield.ai/s/astra-for-editing-higgsfieldai-HQLlcE
2. Or open https://higgsfield.ai/mcp?tab=chatgpt and choose Install Higgsfield plugin.
3. Sign in and authorize. Connector URL if you add it by hand: `https://mcp.higgsfield.ai/mcp`
4. New Astra chat. Enable the Higgsfield tool.
5. Resolve color work in the Production bundle uses `@higgsfield /color-grading`. After Effects motion uses `@higgsfield /use-after-effects`. Those are separate presets from this edit skill.

### B. The editing skill

1. Open https://higgsfield.ai/@adilinthewildtempo/blogs/faster-video-editing-with-astra-higgsfield
2. Download `YT_video_editor_skill_2026-09-22.zip`. Do not commit the zip.
3. Unzip. You get `yt-video-editor-skill/SKILL.md`, `agents/openai.yaml`, and `references/` (`assembly.md`, `briefs.md`, `cameras.md`, `finishing.md`, `learned-examples.md`, `quality.md`, `resolve.md`, `visuals.md`).
4. Install the folder as an agent skill (Codex / ChatGPT skill directory, or drop `SKILL.md` into the project the agent can read).
5. Default prompt from `agents/openai.yaml`:

```
Используй $yt-video-editor-skill: собери рыбу строго по сценарию и подготовь короткие ТЗ поверх нужных кадров по правилам Макса.
```

### C. Sound library

Download `Sound Library.zip` from the same article. 227 files, named `H_SoundLibrary_<n>_<label>.wav` or `.aif`. Whooshes, booms, impacts, UI ticks, vehicles, weather. Import into the Resolve media pool. Do not re-host the audio.

### D. DaVinci Resolve and After Effects

- Resolve Studio, current project open, before the agent writes to the timeline. The skill notes were checked on Resolve Studio 21. Read the installed Scripting README before assuming an API call exists.
- Higgsfield Resolve panel, if you want in-app generation, is a separate install: https://higgsfield.ai/plugins/davinci. Resolve 19+, not the App Store build. Panel lives under Workspace → Workflow Integrations.
- After Effects path for the motion-graphics chapter: plugin from https://higgsfield.ai/plugins/after-effects, then `@higgsfield /use-after-effects`.

## Complete Prompt Library

No generation prompts are printed on the article. These are the copyable texts inside the skill zip.

### 1. Skill manifest

```
interface:
  display_name: "YT_video_editor_skill"
  short_description: "Монтаж YouTube: рыба, ракурсы, ТЗ и проверка"
  default_prompt: "Используй $yt-video-editor-skill: собери рыбу строго по сценарию и подготовь короткие ТЗ поверх нужных кадров по правилам Макса."
```

### 2. SKILL.md (full)

```
---
name: yt-video-editor-skill
description: "Собирать YouTube-видео по правилам Макса: рыба строго по сценарию, монтаж A/B/C, скринкасты и ассеты, короткие ТЗ поверх кадра, моушн и проверка результата. Применять к будущим обучающим выпускам, особенно Higgsfield, и анализу авторских правок в Resolve. Полное производство выполнять только в рамках заказанного этапа."
---

# YT_video_editor_skill

Персональный монтажный процесс Макса. Главная задача — **рыба полностью по сценарию и чёткое, исполнимое ТЗ**. Сокращение и переписывание сценария делает Макс. Новые указания пользователя важнее этого скилла; выводы из отдельного выпуска не подменяют текущий бриф.

## Выполняй заказанный этап

| Запрос | Результат и граница работы |
|---|---|
| Изучить / сравнить финал | Читать проект, смотреть видео, выдать подтверждённые выводы. Монтаж не менять. |
| Собрать рыбу | Удачные дубли в порядке сценария, проверенная речь и синхрон. Если ракурсы пока не заказаны, их не монтировать. Отдать на проверку. |
| Расставить ассеты / написать ТЗ | Сопоставить речь, исходники, камеры и короткие текстовые слои. Это не поручение производить весь моушн. |
| Сделать монтаж / закончить видео | Выполнить разрешённые работы и проверку. Даже автономная работа не разрешает сокращать сценарий. |
| Покрасить / вывести отдельные клипы | Выполнить конкретную операцию, сохранив монтаж и исходники. |

Не требуй повторного согласования разрешённой работы. Если неясен сценарный момент или отсутствует решающий материал, спроси о конкретной реплике/исходнике и продолжай независимые участки. При разрешённой автономной работе решай оформление сам; отсутствующее реальное действие не выдумывай и отмечай как незакрытый материал.

## Начало проекта

1. Установи актуальные проект, таймлайн, FPS и источники. Пользователь мог перемонтировать, переименовать папку или заменить файлы; старый план не доказывает текущее состояние.
2. Определи заказанный этап, сценарий и референсы. Этот скилл самодостаточен: не подключай `youtube-visual-direction`, от которого Макс отказался.
3. Перед правками сохрани восстановимую копию и снимок реальных клипов. Рабочие версии создавай по необходимости, не на каждое действие. Читай [подготовку и рыбу](references/assembly.md).
4. Проверь содержание каждого используемого исходника. Имя, миниатюра и наличие в Media Pool не доказывают полноту материала или соответствие сценарию.

## Речь и структура

- Сохрани все предусмотренные сценарием мысли и порядок. Удалять неудачную попытку, запинку и случайный повтор дубля можно; вырезать запланированное объяснение как «уже понятное» нельзя. Смысловое перефразирование удачного дубля допустимо. Авторские сокращения в референсе не дают права повторять их самостоятельно.
- Последние дубли часто удачны: начинай проверку с них, но оценивай содержание и подачу. Оставляй естественные паузы, дыхание и `I mean`. Не превращай уверенную речь в непрерывную нарезку.
- Речевые склейки ставь между словами или в паузах. Не обрезай фонемы. При скачке позы используй другую синхронную камеру. Проверяй стык в воспроизведении, не только по транскрипту.
- В стандартном трёхкамерном проекте монтаж камер — на V4 копиями; V1–V3 сохраняют синхронные оригиналы. Когда самостоятельная вставка меняет время программы, сдвигай нижние камеры и соответствующий звук вместе с монтажом. Уже согласованную другую структуру не перестраивай молча.
- Принятую покраску и пользовательские правки не меняй попутно. Перед записью сверяй затронутые участки с живым проектом.

## Камера под мысль и визуал

Сначала проверь соответствие реальных исходников этим ролям:

- **A, фронтальный основной:** обращение к зрителю, компактный акцент, два небольших визуала в свободных зонах. A также может быть маленьким окном ведущего поверх крупного скринкаста.
- **B, крупный:** реакция, короткая связка, обещание показа, смена кейса, скрытие несовпадающей позы. На видимую B графику и ассеты не класть. Использовать осмысленно, не исключать полностью.
- **C, боковой общий:** большие карточки, изображения, видео и схемы в свободной части кадра. Сторону выбирай по реальному положению ведущего; не наследуй её из прошлого проекта. Держать камеру, пока развивается объяснение.

В чистой речи без визуалов ориентир смены — около четырёх секунд, с поправкой на фразу и жест. Это не жёсткий таймер. Развивающийся визуал может требовать долгого удержания A/C. Для раскладки и анализа читай [камеры и длительности](references/cameras.md).

## Короткое ТЗ поверх кадра

Формула: **что показать → где/какая камера → на каких словах появляется и меняется → когда уходит**.

> C, слева над креслом. DIRECTION → BLOCKING → FINAL VIDEO. Добавлять по одному на соответствующих словах. Мягкий вход, небольшая перспектива. На «We'll work» убрать.

Давай готовый экранный текст, конкретное действие и источник, если его нужно искать. Общие правила, историю обсуждения и реестр недостающих файлов вынеси из кадра. ТЗ — отдельные редактируемые текстовые слои на соответствующих интервалах; в чистом экспорте выключены, в проекте сохранены. Примеры и проверка исполнимости — [написание ТЗ](references/briefs.md).

## Скринкасты и визуалы

- При объяснении идеи ведущий крупный, иллюстрация рядом. При демонстрации работы интерфейс крупный; маленькая A допустима, если не закрывает действие. Самостоятельный результат — на весь экран.
- В split **чат слева, Blender справа**. Чат кадрируй до разговора; Blender — под действие. Solo chat по умолчанию показывай целиком; осмысленное приближение точного абзаца — отдельный акцент.
- Ускоряй ожидание и длинную работу, чтобы показать существенные действия и результат; оставляй время на чтение. Не используй фризы и короткие петли вместо процесса. Исходные клипы и нативное изменение скорости должны оставлять возможность удлинения.
- Не допускай «моргания»: случайного появления спикера или другого ракурса на несколько кадров между скринкастами, полноэкранными визуалами и следующей вставкой. Проверяй фактическую видимость с учётом верхних слоёв и анимации прозрачности. Связанный показ должен оставаться непрерывным; возвращай ведущего на самостоятельную реплику или реакцию. Способы исправления — в [правилах непрерывности](references/cameras.md#непрерывность-визуалов-без-моргания).
- Длину вставки определяют законченная мысль, действие и время на чтение результата. Скринкаст не должен обрываться посреди ввода слова или до важного результата. Другой участок исходника — прямой кат внутри непрерывной вставки; для ускорения сохраняй полный оригинал и нативное изменение скорости.
- Реальные запрос, ответ и результат должны соответствовать речи. Отмечай конкретное расхождение; не исправляй факты поддельным интерфейсом. Согласованный cleanup служебной плашки допустим с сохранением смысла запроса и результата.
- Случайные чёрные полосы — ошибка. Оформленный фон вокруг карточек — осознанная композиция, применённая в финале. Не растягивай изображение и не срезай нужный интерфейс молча ради заполнения кадра.

Для раскладки, сравнений и анимации читай [визуалы и моушн](references/visuals.md). Для цвета, звука, хука и экспортов — [отделка и выдача](references/finishing.md). Не начинай эти этапы, если заказаны только рыба и ТЗ.

## Resolve и проверка

Предпочитай доступный API для измеримых операций; UI используй для недоступных через API действий и просмотра результата. Не предполагай возможности приложения или плагина. Для автоматизации, XML и Fusion читай [особенности Resolve](references/resolve.md); локальные наблюдения проверяй на установленной версии.

При заказанной уборке таймлайна сохраняй полную архивную версию, группируй действующие слои по назначению и подписывай дорожки. Выключенный клип может быть согласованным вариантом для сравнения; сначала установи его роль. Уборка рабочего таймлайна не означает удаление исходных файлов или перестройку защищённых камер и звука.

Перед сдачей выполняй соответствующие этапу пункты [проверки качества](references/quality.md). Различай анализ структуры, выборочный просмотр, просмотр всей программы в движении со звуком и техническое декодирование. Называй выполненный уровень проверки честно.

В обновлениях сообщай, что готово, что осталось и от чего зависит ETA. Отвечай на вопросы во время работы. Не выдавай план, экспорт настроек или контактный лист за законченный монтаж.

## Как переносить лернинги

[Примеры Blender #2 и Passport Rush](references/learned-examples.md) хранят наблюдения и ограничения. Используй их для решений, а не как обязательные таймкоды, квоты камер, число нод или готовые ассеты следующего выпуска. Обновляй скилл по подтверждённым правкам, различая постоянное правило и решение одного ролика.
```

### 3. On-frame brief examples (full, from references/briefs.md)

```
# Короткое ТЗ для моушн-дизайнера

Формула: **объект/готовый текст → расположение и камера → последовательность по речи → уход**. Заметка должна позволять сразу выполнить действие на нужном кадре.

## Форма в Resolve

- Отдельные редактируемые текстовые слои на понятной дорожке ТЗ. Размести текст так, чтобы можно было оценить и задание, и изображение. Служебное оформление отличается от готовой графики.
- Длина слоя привязана к заданию. В тексте назови слова начала/смены/ухода, если интервала недостаточно. Source in/out и имя файла добавляй для точного поиска.
- Экранный текст — окончательный, в нужном языке. Не заставляй исполнителя выбирать формулировку из длинного списка.
- Общие правила проекта и реестр недостающих материалов — отдельно. На кадре только нужное здесь действие и существенное ограничение.
- Обновляй ТЗ, когда найден материал или принято новое решение. Устаревшее «файл отсутствует» не должно оставаться над найденной записью.
- Служебные слои выключены в чистом экспорте, сохранены в проекте. Проверяй содержимое и включённость, а не только названия дорожек.

## Примеры исполнимых заданий

**Последовательный текст:**

> C, слева над креслом. DIRECTION → BLOCKING → FINAL VIDEO. Добавлять по одному на соответствующих словах. Лаймовый текст, небольшая перспектива, мягкий вход. На «We'll work» убрать.

**Настоящий интерфейс:**

> Чат крупно. Приблизить абзац от «write the lyrics…» до «…move by move», остальной экран приглушить. Выделение держать на этой реплике; текст брать из записи.

**Split с процессом:**

> Чат слева, Blender справа; две скруглённые карточки на тёмном фоне. Ускорить ожидание, показать построение комнаты к «right side». В Blender кадрировать комнату и путь камеры. Дать прочитать результат перед выходом.

Добавь точный файл и source in/out после просмотра. Не подставляй вымышленные координаты.

**Связанные кадры:**

> C, слева три кадра: комната → шланг → контейнер. Появляются по перечислению, соединяются стрелками. На «camera pulls back» показать выход к продуктовому кадру. Убрать перед следующей темой.

**Клиентская правка:**

> Два сообщения по очереди: «Can we change the final angle?» → «OK, sure!». Мягкое появление и короткий набор текста. Держать до конца реплики о правках.

Это иллюстрация диалога. Если нужен настоящий ChatGPT/Astra, используй проверенный интерфейс, не заменяй его общими пузырями.

**Недостающая запись:**

> НУЖЕН SC: установка Blender-плагина. Показать Plugins → Blender → загрузку → установку. Интервал — соответствующая реплика. До получения записи оставить это ТЗ.

Заменяй такой пробел схемой только при согласованном решении; схема объясняет последовательность, а не подтверждает реальное выполнение.

## Что перенять из 27 пометок Макса

Авторские примеры: «добавить текст 3D Jutsu», три строки «Requests / Changes / Results», «скринкаст со старого видео», «скринкаст от Айсаны + моушн», «заполнить фоном», «доработать (подбить по таймингам)», точные границы выделяемой цитаты и готовый текст SMS.

Урок — быстро назвать нужный результат и место. Собственные «заменить»/«доработать» понятны автору из контекста; в передаче исполнителю уточни: **что изменить и на что заменить**. Краткость не должна становиться неопределённостью.

Мои прежние ТЗ перегружались историей поиска, техническими оговорками и повторяющимися запретами. Не пересказывай их поверх кадра. Вместо «сделать красиво» опиши видимый результат; вместо общего «highlight prompt» назови строку; вместо общего «по речи» для сложного перечисления укажи слова-триггеры.

## Проверка

Понятно ли из одной заметки, что появится, где, из какого материала и когда исчезнет? Есть ли для этого место на ракурсе? Готов ли текст, успеет ли зритель прочесть его? Не противоречит ли задание реальному скринкасту? Исправь неопределённость до передачи.
```

## Step-by-Step Recreation Playbook

1. Confirm the video URL is not already in `index.json`. This one is `https://www.youtube.com/watch?v=kOoC3yhUyDQ`.
2. Install the Higgsfield ChatGPT plugin and authorize it.
3. Download the skill zip and the sound zip from the article. Unzip the skill. Point the agent at `SKILL.md`.
4. Open DaVinci Resolve Studio on the same machine as the agent. Save a copy of the project before the first write.
5. Paste the default prompt. Tell the agent the ordered stage: stringout only, then assets and briefs, then finish. The skill forbids cutting scripted thoughts and forbids inventing a missing action.
6. For the commercial: generate the "Editing Has Changed" shots in Higgsfield, import them, then ask Astra to cut to the script and lay SFX from `Sound Library`.
7. Refine pacing on the timeline. Keep source clips linked. Do not replace a retimed clip with a baked compound. The skill's Resolve notes say to re-read clip bounds after a ripple.
8. Rebuild the YouTube section by matching speech to screen recordings and B-roll. If a recording is missing, leave an on-frame brief that says the file is missing. Do not fake the UI.
9. Color: ask for the grade on a copy. Production preset if you want the bundle path: `@higgsfield /color-grading`. The skill's preferred studio-camera LUT name, when that LUT is in the project, is Higgs YT V3. Do not stack it twice. Do not grade screencasts with the camera LUT.
10. Motion graphics: switch to After Effects with the Higgsfield plugin signed in. Command: `@higgsfield /use-after-effects`. Keep type as live text.
11. Shorts: duplicate the timeline, reframe to 9:16, keep speech, drop lines that need the wide frame. Do not letterbox-scale the master.
12. Before delivery, name the check you actually ran: structure only, spot check, or full program with sound.

## Key Learnings & Replication Notes

- The article is a download page. The prompts live in the zip, in Russian. Do not translate them and call the translation the skill.
- Stage boundaries matter. "Assemble the stringout" is not permission to design motion or grade.
- New user instructions beat the skill. Notes from Blender #2 and Passport Rush in `learned-examples.md` are constraints, not timecodes to copy.
- On-frame briefs use this shape: object or final text, placement and camera, order against the spoken line, exit. One note must say what appears, where, from which file, and when it leaves.
- Missing footage stays marked missing. A diagram is allowed only if the user agreed it explains a sequence, not that the action happened.
- Resolve API calls are version-specific. The skill says to test on a short known range before a timeline-wide write, and not to edit during a render.
- Sound library is stock SFX, not a music bed. Music end points in `finishing.md` (fade by about 16 seconds on one Blender episode) are episode-specific. Do not reuse that duration.

## Raw Links

- Video: https://www.youtube.com/watch?v=kOoC3yhUyDQ
- Install MCP: https://higgsfield.ai/s/astra-for-editing-higgsfieldai-HQLlcE
- Skill + SFX page: https://higgsfield.ai/s/astra-for-editing-higgsfieldai-XqLQyi
- Article: https://higgsfield.ai/@adilinthewildtempo/blogs/faster-video-editing-with-astra-higgsfield
- ChatGPT plugin: https://higgsfield.ai/mcp?tab=chatgpt
- MCP: https://mcp.higgsfield.ai/mcp
- Resolve plugin: https://higgsfield.ai/plugins/davinci
- After Effects plugin: https://higgsfield.ai/plugins/after-effects
- Discord: https://discord.gg/higgsfield
- Instagram: https://www.instagram.com/higgsfield.ai/
- Reddit: https://www.reddit.com/r/HiggsfieldAI/
