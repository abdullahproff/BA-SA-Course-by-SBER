# Домашнее задание 1 - теория

Учимся писать пользовательские истории (user story).

School 21: mhorton

## Образовач

Из русского перевода BABOK v3:

> Пользовательская история (ПИ) - описание функциональности или качества, необходимых конкретной заинтересованной стороне для получения пользы.

ПИ закрепляют (фиксируют) потребности конкретной
заинтересованной стороны и позволяют командам определять ценные
для заинтересованной стороны свойства, используя краткую простую
документацию. Обычно пользовательская история — это одно-
два предложения, описывающие, кто имеет рассматриваемую историей
потребность, цель, которую пользователь пытается достичь, и любую
дополнительную информацию, критичную для понимания содержания
истории.

Составляющие ПИ:

1. **Кто**. Это не обязательно только физическое лицо (ФЛ), но и вообще сущность (пример, внешняя система), которая может использовать целевую (описываемую) систему.
2. **Что**. Здесь выражается требуемое действие\поведение\качество и т.д. - что хотят видеть в целевой системе или что она должна уметь.
3. **Почему**. Выгода\Ценность, достигаемые при осуществлении желаемого\требования* **Чего** для **Кого**.

Это обычно подаётся как следующее лекало:

**Кто-то** (сущность) как **Пользователь или Роль + возможное указание системы\подсистемы**
**Желает\Требует\Хочет\...** (глагол изъявления требования) функциональность\хотелка\...
**Чтобы\Для\...** (описание достигаемой цели\потребности\...)

Пример:

**Федеральная налоговая служба** (пользователь) как (уточнение пользовательской роли) внешний надзорный орган
**Требует** выбирать разные форматы выгрузки отчётов ХХХ
**Чтобы** получать данные в нужных форматах без дополнительных усилий по преобразованию данных из одного формата в другие

Как-то так, пусть и подкривовато...

Желательно не смешивать несколько требований в одно,
но это, скорее, сильное пожелание, а не требование.
Т.е., "хочу А и Б, но если не Б, то В" говорит о двух требованиях
да ещё и обусловленных (кондициональных).
Их можно разделить на две, тем самым почтить правило
атомарности (дальнейшей "неделимости").

## Источники

- [Гайд по написанию пользовательских историй и критериев приёмки - Habr.ru](https://habr.com/ru/companies/X5Tech/articles/723742/)
- [Что такое User Story и как её создать - Practicum.Yandex](https://practicum.yandex.ru/blog/chto-takoe-user-story-i-kak-napisat/)
