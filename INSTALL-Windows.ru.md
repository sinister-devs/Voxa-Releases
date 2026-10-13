# Voxa для Windows 11 — 0.2.1 beta

[Setup EXE](https://github.com/sinister-devs/Voxa-Releases/releases/download/v0.2.1-windows-beta.1/Voxa-0.2.1-Windows-x64-Setup.exe) · [Portable ZIP](https://github.com/sinister-devs/Voxa-Releases/releases/download/v0.2.1-windows-beta.1/Voxa-0.2.1-Windows-x64-Portable.zip) · [SHA256 и заметки](https://github.com/sinister-devs/Voxa-Releases/releases/tag/v0.2.1-windows-beta.1)

Это прежняя beta от21.09.2026, перенесённая без изменения файлов13.10.2026. Она не пересобиралась с обновлениями Mac Dev27.54. Требуется Windows11 x64. Приложение использует личный OpenAI API-ключ и отдельную оплату API; подключения серверных подписок здесь нет.

1. Сверьте SHA256 с SHA256SUMS.txt на странице релиза.
2. Закройте Voxa и запустите Setup EXE. Установка выполняется для текущего пользователя; права администратора не нужны. Настройки, история и credentials Windows Credential Manager сохраняются.
3. Для portable распакуйте весь ZIP в отдельную папку и запустите Voxa.exe. Не копируйте отдельно EXE: нужны соседние файлы.
4. Настройте API-ключ и микрофон, проверьте диктовку, шорткаты и вставку на своём компьютере.

Beta не подписана цифровым сертификатом. Windows может показать предупреждение. Проверяйте источник и контрольную сумму; не отключайте системные защиты. Нативные проверки Windows при этом переносе не повторялись.

Аудио и текст для запрошенной обработки отправляются в OpenAI. API-ключ хранится в Windows Credential Manager. Локальная история и записи этой старой Windows beta не зашифрованы самим приложением. Не отправляйте ключи, личные записи или историю в публичные issues.
