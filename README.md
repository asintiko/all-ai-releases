# ALL AI — релизы

Установщики десктоп-приложения **ALL AI** и файл автообновления. Исходный код хранится в отдельном приватном репозитории.

**Скачать:** [последний релиз](https://github.com/asintiko/all-ai-releases/releases/latest)

| Система | Файл |
|---|---|
| Windows 10/11 x64 | `ALL.AI_<версия>_x64-setup.exe` — установка без прав администратора |
| macOS 11+ (Apple Silicon и Intel) | `ALL.AI_<версия>_universal.dmg` |

Приложение само проверяет обновления и ставит их по вашему согласию.

## macOS: первый запуск
Пока сборка не подписана сертификатом Apple Developer ID, Gatekeeper может сказать, что приложение «повреждено» или «от неустановленного разработчика». Откройте его так:

1. Перетащите **ALL AI** в «Программы».
2. В Finder нажмите на приложение правой кнопкой → **Открыть** → **Открыть**.
3. Если macOS пишет «повреждено», выполните в Терминале:
   ```bash
   xattr -dr com.apple.quarantine "/Applications/ALL AI.app"
   ```

## Windows: SmartScreen
Пока установщик не подписан сертификатом, SmartScreen может показать «Windows защитила ваш компьютер». Нажмите **Подробнее** → **Выполнить в любом случае**.

---

Installers and the auto-update feed for the **ALL AI** desktop app. Official installers are free to install and use; see the license shipped with the app. The source code is not public.
