# Пользователь (User)

{% include [Черновик](../../../_includes/draft.md) %}

Учётная запись пользователя информационной системы ЛизаАлерт.

## Назначение модели

1. Хранение учётных данных пользователя.
2. Хранение прав пользователя в ИС.
3. Хранение контактных данных пользователя.

## Ключевые особенности

…

## Требования к модели

…

## Свойства

{% include [Условные обозначения](../../../_includes/entity-legend.md) %}

#|
|| Свойство | Тип | Ограничения | Описание ||
|| ##id## 🔑 | Целое число | > 0 | Идентификатор пользователя ||
|| ##additionalEmails## | [UserAdditionalEmails] | ??? | Дополнительные адреса электронной почты ||
|| ##additionalPhones## | [UserAdditionalPhones] | ??? | Дополнительные номера телефонов ||
|| ##calls## | [Call] | ??? | ??? ||
|| ##email## | Строка | Обязательное | Основной адрес электронной почты ||
|| ##equipments## | [Equipment] | ??? | ??? ||
|| ##groups## | [Group!] | ??? | ??? ||
|| ##isShiftActive## | да/нет | Обязательное | Находится сейчас на смене? ||
|| ##issues## | [Issue] | ??? | ??? ||
|| ##privateMessages## | [PrivateMessage] | ??? | ??? ||
|| ##profile## | Profile! | ??? | ??? ||
|| ##regions## | [Region!] | ??? | ??? ||
|| ##tasks## | [Task] | ??? | ??? ||
|| ##team## | Team | ??? | ??? ||
|| ##technics## | [Technic] | ??? | ??? ||
|| ##userPermissions## | [String] | ??? | ??? ||
|| ##vigilGroups## | [Group!] | ??? | ??? ||
|#