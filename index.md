---
layout: default
title: Хартия — политика конфиденциальности
lang: ru
---

# Политика конфиденциальности приложения «Хартия» / Privacy Policy

_Последнее обновление: 12 ноября 2026 г._

## Русская версия

Приложение **«Хартия» (`app.chartia.sheet`)** создано по принципу **100% Local-First и полной автономности**. Мы убеждены, что ваши игровые листы персонажей, заметки кампаний и настройки принадлежат только вам.

### 1. Полное отсутствие доступа в интернет
В манифесте Android-приложения (`AndroidManifest.xml`) **намеренно отсутствует разрешение `android.permission.INTERNET`**. Операционная система Android на системном уровне запрещает «Хартии» устанавливать любые сетевые соединения, отправлять запросы или связываться с внешними серверами.

### 2. Какие данные мы собираем
**Никаких.** Приложение:
- не требует регистрации или создания учётной записи;
- не собирает персональные данные, имя, email, номер телефона или геолокацию;
- не собирает идентификаторы устройства, IP-адреса, аналитику использования или телеметрию;
- не содержит сторонних рекламных, аналитических или трекинговых SDK (включая Google Play Services, Firebase Analytics, Crashlytics и др.).

### 3. Где хранятся ваши данные
Все созданные вами листы персонажей и настройки приложения хранятся исключительно локально во внутренней изолированной директории приложения на вашем устройстве (`files/characters/*.json`). При удалении приложения операционная система Android полностью очищает эту директорию.

### 4. Импорт и экспорт файлов
Чтение и сохранение файлов `.json` во внешнюю память устройства или передача листа через системное меню «Поделиться» происходят исключительно по вашему явному действию с использованием стандартных системных механизмов Android (`Storage Access Framework` и `FileProvider`), без запрашивания глобального доступа ко всем файлам на телефоне.

### 5. Связь с разработчиком
Вопросы о конфиденциальности и работе приложения можно задать через раздел Issues репозитория: https://github.com/vutnar21-cmd/Chartia-Character-list/issues

---

## English Version

**Chartia (`app.chartia.sheet`)** is built from the ground up as a **100% Local-First, offline-only application**.

### 1. Zero Network Access
The application manifest (`AndroidManifest.xml`) **intentionally omits the `android.permission.INTERNET` permission**. The Android operating system strictly prevents Chartia from making any incoming or outgoing network connections.

### 2. Data Collection
**None.** Chartia does not collect, store on external servers, or share any personal data, device identifiers, usage telemetry, crash logs, or location data. The app contains zero advertising, analytics, or proprietary tracking SDKs.

### 3. Local Storage & User Control
All character sheets, campaign notes, and preferences are stored exclusively on your device in the app's private internal storage directory as open `.json` files. Exporting or sharing a `.json` file only occurs when explicitly initiated by the user via standard Android system dialogs (`Storage Access Framework` and `FileProvider`).

### 4. Contact
Questions about privacy or the app can be submitted via the repository Issues page: https://github.com/vutnar21-cmd/Chartia-Character-list/issues
