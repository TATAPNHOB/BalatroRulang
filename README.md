# BalatroRulang
Патч русской локализации Balatro для версии v1.0.1, исправляющий ошибки и добавляющий кириллический шрифт
Balatro v1.0.1's Russian Localization Patch, correcting linguistic and logical errors and adding a custom font with cyrillic glyphs
---
## Как установить?
1. Скачать архив последней версии lovely-injector из [их репозитория](https://github.com/ethangreen-dev/lovely-injector/releases)
2. Извлечь файл `version.dll` в папку `...Steam/steamapps/common/Balatro` (чтобы найти папку: ПКМ по игре в списке игр в библиотеке в Steam, "просмотреть локальные файлы")
3. Открыть папку `AppData/Roaming/Balatro` (чтобы найти папку: Win+R, ввести `%appdata%` и нажать Enter, найти в списке папку Balatro) и извлечь файлы из последнего [релиза патча](https://github.com/TATAPNHOB/balatrorulang/releases)
4. Открыть игру через Steam

### ГЛОБАЛЬНЫЕ ИЗМЕНЕНИЯ
- Теги теперь жетоны
- Ваучеры теперь талоны
- "Ослабление" карт и джокеров теперь называется "блокировкой" карт
- "Перезапуск карт" теперь называется "сыграть карты заново/ещё раз"
- "Карты с лицом" везде переименованы как "лицевые карты"
- "Играемые карты" переименованы по контексту в "игральные карты"
- Размер руки как правило отформатировано, чтобы число шло после идентификатора (напр. "Размер руки +1")
- Х-множ. как правило отформатировано, чтобы число шло после идентификатора (напр. "Множ. Х3...")
- Плюс-множ. как правило отформатировано, чтобы число шло перед идентификатором (напр. "+10 множ...")
- Убраны ненужные сокращения слов в описаниях карт
- В ненужных местах дополнительные окончания в связи с родами зависимых слов убраны и добавлены в зависимости от того, требует ли это контекст
- Везде, где упоминаются деньги, знак доллара стоит перед числом (напр. $100)
- Джокеры, которые накапливают множ., х-множ. или фишки, теперь имеют в описании прямое упоминание этого
- Джимбо теперь обращается на "ты" в туториале
- Предлоги и союзы в конце строк перенесены на следующую строку
- Описания карт упрощены для понимания и лучше отражают способности

### ИЗМЕНЕНИЯ В НАЗВАНИЯХ ДЖОКЕРОВ
- Бизнес-карта (Business Card) > Визитка
- Клоун Хаос (Chaos Clown) > Клоун Хаоса
- Рифф-рафф (Riff-raff) > Всякий сброд
- Мастер колец (Ring Master) > Хозяин манежа
- Трусливый джокер (Wee Joker) > Крохотный джокер 
- Острая карта (Card Sharp) > Острый шулер
- Зельцер (Seltzer) > Минералка
- Торговая карта (Trading Card) > Коллекционная карточка
- Бутстрэп (Bootstraps) > Подтяжки
- Улыбочка (Smiley Face) > Доброе лицо
- Упс! Все шестерки (Oops! All 6s) > Все шестёрки
- Еще разок (Hanging Chad) > Недооторванный кусочек
- В путь (Hit the Road) > Вали, валет
- До Луны (To the Moon) > К звёздам
- На Луну (Shoot the Moon) > Выстрел по Луне
- Всё че(с)тно (Even Steven) > Честный Валя
- Нече(с)тные правила (Odd Todd) > Нечестный Коля
- Веселый Энди (Merry Andy) > Весёлый Вова
- Полуджокер (Half-Joker) > Полушут
- Возврат (Throwback) > Флешбэк
- Эрозия (Erosion) > Размывание
- Ученый (Scholar) > Студент
- Космический джокер (Space Joker) > Астронавт
- Трагедия и комедия (Sock and Buskin) > Трагикомедия

### ИЗМЕНЕНИЯ В НАЗВАНИЯХ ТАЛОНОВ (ВАУЧЕРОВ)
- Подъемные (Seed Money) > Откат
- Кисть для рисования (Paint Brush) > Кисточка
- Избыток плюс (Overstock Plus) > Переизбыток
- Магнат Таро (Tarot Tycoon) > Таро-магнат
- Магнат планет (Planet Tycoon) > Планетарный магнат
- Начо Тонг (Nacho Tong) > Начо-щипцы
- Рецикломантия (Recyclomancy) > Отходотургия

### ИЗМЕНЕНИЯ В НАЗВАНИЯХ КАРТ ТАРО
- Верховная Жрица (High Priestess) > Верховная жрица

### ИЗМЕНЕНИЯ В НАИМЕНОВАНИЯХ ВЫПУСКОВ КАРТ
- Фольговый (Foil) > Фольгированный

### ИЗМЕНЕНИЯ В НАЗВАНИЯХ ЖЕТОНОВ (ТЕГОВ)
- Мусорный жетон (Garbage Tag) > Заброшенный жетон
- Жетон купона (Coupon Tag) > Скидочный жетон
- Жетон D6 (D6 Tag) > К6-жетон


### ИЗМЕНЕНИЯ В НАЗВАНИЯХ ИСПЫТАНИЙ
- 15-минутный город (15 Minute City) > Пешеходная доступность
- Не портится (Non-Perishable) > Нескоропортящееся
- Одно и то же (Typecast) > Закрепление типажа
- Хрупкое (Fragile) > Хрупкие руки

### ПРОЧИЕ ИЗМЕНЕНИЯ
- Джамбо-наборы (Jumbo Booster Packs) теперь называются супер-наборами
