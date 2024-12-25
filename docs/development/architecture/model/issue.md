# Заявка на поиск (Issue)

{% include [Черновик](../../../_includes/draft.md) %}

Модель [Заявки на поиск](../../../domain/data/issue.md).

## Назначение модели

…

## Ключевые особенности

…

## Требования к модели

…

## Свойства

{% include [Условные обозначения](../../../_includes/entity-legend.md) %}

#|
|| Свойство | Тип | Ограничения | Описание ||
|| ##id## 🔑 | Целое число | > 0 | Идентификатор заявки ||
|| ##additionalRegions## | `[Region]` | ??? | Дополнительные регионы поиска? ||
|| ##bearers## | `[IssueBearer]` | ??? | Заявители? ||
|| ##callCount## | Целое число | Обязательное, ≥ 0 | ??? ||
|| ##callRequestCount## | Целое число | Обязательное, ≥ 0 | ??? ||
|| ##callRequests## | `[CallRequest]` | ??? | ??? ||
|| ##callingCount## | Целое число | Обязательное, ≥ 0 | ??? ||
|| ##callings## | `[Calling]` | ??? | ??? ||
|| ##calls## | `[Call]` | ??? | ??? ||
|| ##childIssues## | `[Issue]` | ??? | ??? ||
|| ##commentCount## | Целое число | Обязательное, ≥ 0 | ??? ||
|| ##comments## | `[IssueComment]` | ??? | ??? ||
|| ##createdBy## | [{#T}](user.md) | | Пользователь, добавивший заявку в систему ||
|| ##created_at## | `String` | ??? | Время создания заявки ||
|| ##date_of_loss## | `String` | ??? | Дата пропажи ||
|| ##districts## | `[District]` | ??? | ??? ||
|| ##forum_theme## | Строка | ??? | URI темы на форуме ЛизаАлерт ||
|| ##is_draft## | да/нет | ??? | ??? ||
|| ##is_email_submitted## | да/нет | ??? | ??? ||
|| ##is_emergency## | да/нет | ??? | ??? ||
|| ##is_forest_online## | да/нет | ??? | ??? ||
|| ##is_reverse_lookup## | да/нет | ??? | ??? ||
|| ##is_sms_submitted## | да/нет | ??? | ??? ||
|| ##is_training## | да/нет | ??? | ??? ||
|| ##last_seen_location## | Строка | ??? | ??? ||
|| ##letterCount## | Целое число | Обязательное, ≥ 0 | ??? ||
|| ##letters## | `[Letter]` | ??? | ??? ||
|| ##maps## | `[IssueMap]` | ??? | ??? ||
|| ##media_publications## | Строка | ??? | ??? ||
|| ##missing## | `[IssueMissing]` | ??? | ??? ||
|| ##office_coordinates## | Строка | ??? | ??? ||
|| ##parentIssue## | `Issue` | ??? | ??? ||
|| ##participants## | `[Participant]` | ??? | ??? ||
|| ##reason_of_loss## | Строка | ??? | ??? ||
|| ##region## | `Region` | ??? | ??? ||
|| ##reports## | `[IssueReport]` | ??? | ??? ||
|| ##searchLocation## | `SearchLocation` | ??? | ??? ||
|| ##social_network_theme## | Строка | ??? | ??? ||
|| ##source## | `IssueSource` | ??? | ??? ||
|| ##taskCount## | Целое число | Обязательное, ≥ 0 | ??? ||
|| ##tasks## | `[Task]` | ??? | ??? ||
|| ##teams## | `[Team]` | ??? | ??? ||
|| ##verifications## | `[IssueVerification]` | ??? | ??? ||
|#
