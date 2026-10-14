# rules-qwen

Единый источник истины для настройки агента Qwen Code. Адаптация
[rules-zed](https://github.com/IgerOK/rules-zed) под Qwen Code.

## Состав

| Файл | Назначение |
|---|---|
| `rules-Qwen.md` | Канон-инструкция (5 разделов) |
| `AGENTS.md` | Контекст проекта + автозапуск развёртывания |
| `skills/git-workflow/SKILL.md` | Skill git-workflow |
| `skills/project-doctor/SKILL.md` | Skill project-doctor |
| `.gitignore` | Игнорируемые файлы |
| `LICENSE` | MIT |

## Использование

1. Установить [Qwen-Code-Desktop_0.25.1_x64-setup.exe](https://github.com/QwenLM/qwen-code/releases/download/desktop-v0.25.1/Qwen-Code-Desktop_0.25.1_x64-setup.exe) и [Git](https://git-scm.com/).
2. Скачать проект (Download ZIP), открыть папку в Qwen Code.
3. При первом открытии агент читает `AGENTS.md`, видит отсутствие установленных
   файлов и развёртывает правила сам. Если нет — в **новом** чате сказать:
   «Прочитай файл `rules-Qwen.md` и выполни инструкции §1–§5».
4. Проверить, что создан глобальный `~/.qwen/QWEN.md` и доступны skills.
5. В новом чате проверить, что правила применяются.

## Конфиденциальность

В файлах только плейсхолдеры, секретов нет. API-ключи — только в настройках
Qwen Code, в файлы проекта не попадают.

## Лицензия

MIT — см. `LICENSE`.
