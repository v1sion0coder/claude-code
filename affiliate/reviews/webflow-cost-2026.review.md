# Ревью: webflow-cost-2026 — editorial package (Codex/GPT) + вердикт (Claude)

- **Исполнитель (editor):** GPT/Codex (локально, AI_OFFICE). Пакет передан владельцем в чат
  (push из-за лимита Codex не прошёл), интегрирован Claude вручную 2026-09-22.
- **Reviewer:** Claude (reviewer_ai).
- **Вердикт reviewer:** ПРИНЯТО. Улучшенный вариант GPT внесён в мастер-файл
  `affiliate/content/Webflow/webflow-cost-2026.md`. Статья остаётся DRAFT — публикация только
  после пред-публикационных проверок (реальные цены, реальный {{AFF_LINK}}, сверка ссылок).

## Проверка по 4 правилам честности
1. Источники: цитируемые факты снабжены ссылками на офиц. Help Center Webflow — **pass**
   (ссылки перепроверить в день публикации).
2. «Прибыль» = только paid: статья ничего о доходе не утверждает — **pass**.
3. Не выдуманы цифры/лимиты: конкретные цены удалены, везде «verify on webflow.com» — **pass**.
4. Disclosure + {{AFF_LINK}} + без обещаний: на месте; убран намёк на личный тест — **pass**.

## Что исправил GPT (принято)
1. Site vs Workspace — разведены (были смешаны как «хостинг»).
2. Ecommerce — это вариант Site-плана, а не вторая подписка сверху.
3. Удалены выдуманные диапазоны цены домена ($10–20/год).
4. Убраны категоричные сравнения (WordPress «всегда с платными плагинами»; Shopify «сильнее»;
   «блог обязателен для SEO»; «миграция проще, чем у WordPress»).
5. Free-tier сужен до «оценки в рамках лимитов».
6. Убран намёк на hands-on-тест продукта («Real Breakdown», опыт автора).

## Замечание reviewer
Версия честная, но местами суховата (частые «verify on webflow.com»). Перед публикацией
допустимо слегка оживить подачу — БЕЗ возврата непроверенных утверждений и без намёка на
личный тест.

---

## H1-варианты (от GPT)
1. How Much Does a Webflow Website Cost in 2026? Plans and Extras Explained
2. How Much Does a Webflow Website Cost? A First-Year Budget Guide
3. Webflow Website Costs: What to Budget Beyond the Site Plan
4. How Much Does a Webflow Website Cost for a Portfolio, Blog or Store?
5. Webflow Pricing Explained: Site Plans, Workspaces and Website Costs
(Редакторские гипотезы, не измеренный CTR.)

## Карта запросов (гипотезы, без измеренного объёма)
| Фраза | Интент | Размещение |
|---|---|---|
| how much does a webflow website cost | pricing | H1 + интро |
| webflow website cost per year | pricing | Бюджет-примеры |
| webflow site plan vs workspace plan | comparison | 1-я секция затрат |
| webflow free vs paid plan | comparison | Free / FAQ |
| do I need a paid workspace for webflow | how-to | FAQ |
| webflow blog website cost | pricing | Content-site пример |
| webflow ecommerce website cost | pricing | Ecommerce секция |
| webflow vs wordpress total cost | comparison | кратко; отдельная статья |
| how to budget for a webflow website | how-to | Бюджет-итог |
| webflow pricing review | review | вспомогательно, без hands-on |

## Чек-лист перед публикацией (от GPT, принят)
- Сверить актуальные названия/лимиты планов под реальный аккаунт; на странице цен смешанные
  ярлыки — не реконструировать тариф-таблицу вслепую.
- Проставить датированные офиц. цены (валюта, период биллинга, налоги, дата проверки).
- Проверить требования Site/Workspace, лимиты CMS, комиссии Ecommerce под сценарий.
- Подтвердить цену покупки и продления домена у регистратора.
- Сверить детали экспорта/миграции по актуальной документации.
- Подтвердить приём в партнёрку и авторизованный referral-URL; тестировать трекинг только
  разрешённым способом.
- Disclosure — вверху и у CTA. Не публиковать плейсхолдер как рабочую ссылку.
- Проверить синтаксис UTM/subid1, а не считать его поддерживаемым по умолчанию.
- Удалить любые утверждения о личном опыте, которые нельзя подтвердить.
- Приоритеты ключей — гипотезы, пока нет реальных данных.
- Публикацию одобряет владелец. Этим ревью ничего не опубликовано.
