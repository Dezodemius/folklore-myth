# Колодец преданий — фольклор и мифы

Колодец народных сюжетов: фольклор, мифы и священные тексты (славянская, восточноазиатская, индийская, библейская, греческая, скандинавская традиции). Достаёт архетипический сюжет, мотив или фигуру и адаптирует под тему пользователя со «снятым серийником»: свежая история, а не пересказ. Инструменты: морфология Проппа, мономиф, архетипы. Используй, когда просят «сюжет из фольклора / мифа / сказки / легенды», «славянский / азиатский / библейский сюжет», «по мотивам мифов», «мифологическая основа истории», «квест на основе мифа». Заточен под D&D: результат готов для writers-council и dnd-master. Вывод на русском.

Скилл в формате [Agent Skills](https://agentskills.io): работает в Claude, Codex, Gemini CLI и других ИИ-агентах, а однофайловая версия — в любом чате.

## Примеры запросов

> Возьми славянский сюжет для квеста на 2 сессии про пропавших детей.

> Дай мифологическую основу для злодея-некроманта по мотивам скандинавских мифов.

> Совет традиций: тема «город, где запрещено спать».

## Установка

Готовые файлы лежат в [релизах](https://github.com/Dezodemius/folklore-myth/releases/latest).

| Где пользуетесь | Как подключить |
| --- | --- |
| **claude.ai**, Claude Desktop | Скачать [`folklore-myth.zip`](https://github.com/Dezodemius/folklore-myth/releases/latest/download/folklore-myth.zip) → Настройки → Возможности → Skills → загрузить. В Desktop можно открыть [`folklore-myth.skill`](https://github.com/Dezodemius/folklore-myth/releases/latest/download/folklore-myth.skill) двойным кликом |
| **Claude Code** | `/plugin marketplace add Dezodemius/agent-skills`, затем `/plugin install folklore-myth@dezodemius-skills` |
| **Codex, Gemini CLI, Cursor, GitHub Copilot, OpenCode** и другие агенты | `npx skills add Dezodemius/folklore-myth` |
| **ChatGPT, Gemini, DeepSeek, Qwen, Grok, Алиса, GigaChat** и другие чаты | Скачать [`folklore-myth.prompt.md`](https://github.com/Dezodemius/folklore-myth/releases/latest/download/folklore-myth.prompt.md) и приложить в начале чата или вставить в инструкции проекта / GPT / Gem |

Подробно по каждой платформе — в [каталоге](https://github.com/Dezodemius/agent-skills#установка).

## Связка D&D-скиллов

Скиллы работают и по отдельности, и цепочкой: сюжет → механика → книга.

| Скилл | Роль |
| --- | --- |
| [folklore-myth](https://github.com/Dezodemius/folklore-myth) | сюжетная основа из мифов и фольклора |
| [writers-council](https://github.com/Dezodemius/writers-council) | консилиум писателей разворачивает тему в сюжет |
| [pantheons](https://github.com/Dezodemius/pantheons) | боги, культы, домены жрецов |
| [dnd-master](https://github.com/Dezodemius/dnd-master) | правила 5e, баланс, NPC, локации |
| [dnd-module](https://github.com/Dezodemius/dnd-module) | вёрстка в книгу-модуль, наполнение карты |

Полный каталог: [Dezodemius/agent-skills](https://github.com/Dezodemius/agent-skills).

## Выпуск релиза

Релиз собирается автоматически по тегу из четырёх чисел на коммите из `main`:

```bash
git tag 1.0.0.0 && git push origin 1.0.0.0
```

Общий CD и проверки живут в [Dezodemius/agent-skills](https://github.com/Dezodemius/agent-skills).

## Лицензия

Apache License 2.0 — см. [LICENSE](LICENSE) и [NOTICE](NOTICE).
