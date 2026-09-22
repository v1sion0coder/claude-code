id: TASK-001
title: Независимое ревью статьи "How Much Does a Webflow Website Cost in 2026"
owner_ai: codex
reviewer_ai: claude
status: open
inputs: affiliate/content/Webflow/webflow-cost-2026.md
allowed_changes: создать ТОЛЬКО новый файл affiliate/reviews/webflow-cost-2026.review.md. Сам исходник статьи НЕ редактировать.
done_criteria: >
  Файл-ревью содержит:
  (1) проверку 4 правил честности с явным вердиктом pass/fail по каждому:
      - affiliate-disclosure присутствует и корректен;
      - плейсхолдер {{AFF_LINK}} на месте, реальной ссылки нет;
      - нет выдуманных цен/цифр/лимитов (везде, где нет источника, стоит "verify on webflow.com");
      - нет обещаний дохода/трудоустройства/гарантий;
  (2) 5-8 замечаний по SEO/ясности/структуре (заголовок, интро, H2/H3, CTA, FAQ) с конкретикой;
  (3) список того, что владелец обязан проверить/подставить перед публикацией;
  (4) итоговый вердикт: готова к правкам / требует доработки.
output: affiliate/reviews/webflow-cost-2026.review.md

---

## Контекст для исполнителя (Codex)
Это первая пробная файловая задача для отладки связки двух AI. Она намеренно маленькая,
безопасная и без коннекторов: только чтение одного файла и создание одного файла-ревью.

Порядок:
1. Захвати задачу: смени `status: open` → `status: claimed`, commit+push.
2. Прочитай `affiliate/content/Webflow/webflow-cost-2026.md` и правила честности в
   корневом `CLAUDE.md` (раздел «Незыблемые правила»).
3. Напиши ревью в `affiliate/reviews/webflow-cost-2026.review.md` по `done_criteria`.
4. Смени `status: in_review`, commit+push.
5. Claude (reviewer_ai) сверит результат и либо примет правки в статью, либо вернёт замечания.

Не редактируй CSV, не трогай другие статьи, не подключай коннекторы, ничего не публикуй.
