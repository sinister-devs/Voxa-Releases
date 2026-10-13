# Установка Voxa Dev 27.53

[Скачать Mac Dev beta](https://github.com/sinister-devs/Voxa-Releases/releases/download/v27.53-macos-dev-beta.1/Voxa-27.53-universal.dmg)

Требуется macOS 14 или новее. Один DMG поддерживает Apple Silicon и Intel. Это Dev-версия с личным OpenAI API-ключом и отдельной оплатой API. Prod с сервером и подписками пока не опубликована.

1. Сверьте SHA256 файла с SHA256SUMS.txt на [странице релиза](https://github.com/sinister-devs/Voxa-Releases/releases/tag/v27.53-macos-dev-beta.1).
2. Закройте предыдущую Voxa. Откройте DMG и перетащите Voxa.app в Applications. Приложение называется Voxa Dev.
3. Запустите его из Applications и настройте API-ключ, микрофон, Accessibility и шорткаты. Перед обновлением сохраните резервную копию своей истории и записей.

Beta подписана Apple Development сертификатом; Developer ID и нотариализации нет. macOS может заблокировать первый запуск. После проверки источника и контрольной суммы разрешите запуск через System Settings → Privacy & Security → Open Anyway. Не выключайте Gatekeeper.

Приложение использует прежний идентификатор Mac beta. Вставка и обучение исправлениям зависят от того, как редактор раскрывает текст через Accessibility. Проверяйте полученный текст перед отправкой.

Ключ сохраняется в macOS Keychain. При запрошенной AI-обработке необходимые аудио и текст отправляются провайдеру. Не публикуйте ключи, личные тексты, историю или записи в GitHub. Windows-инсталляторы в этот репозиторий пока не перенесены; Android-приложение пока отсутствует.
