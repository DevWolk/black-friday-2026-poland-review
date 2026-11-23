# Проверка отчёта второй модели и что применено в Notion (22.11.2026)

Отчёт: `review-report-22-11.md`. Цены ниже открыты в браузере 22.11.2026, если не сказано иное.

## Опровергнуто

| Утверждение отчёта | Что на странице 22.11 |
|---|---|
| Notino Parlux Alyon: код notino −15% = 560,15 zł, ниже минимума 585 | «659,00 zł», «593,10 zł z kodem NOTINO», «Aktualna cena 659,00 zł -10%», «Ostatnia najniższa cena 585,00 zł +1%». Реальной скидки нет |
| Amazon Parlux: сторонний продавец Liguori, 555,46 + 24,00 = 579,46 zł | «527,69 zł … -5%», «Najniższa cena z 30 dni przed obniżką: 555,46 zł», «Sprzedawca / Wysyłka Hair Gallery», «DARMOWA dostawa 28 listopada - 1 grudnia» |
| 8a.pl BUFF Solid Light Grey распродан | Кнопка «DODAJ DO KOSZYKA», «Ostatnie sztuki», «96,99 zł», «Najniższa cena w okresie 30 dni przed obniżką 87,99 zł (+11%)» |
| Sportano BUFF Light Grey 89,99 zł | «109,99 zł bez kodu», «93,49 zł z kodem», «Najniższa cena z 30 dni przed obniżką: 85,49 zł» |
| Media Expert UGREEN US264 13,90 zł | «17,90 zł» (как в x-kom) |
| Biedronka Home: Dreame Pocket Pro и MG Home распроданы | Обе страницы с «DODAJ DO KOSZYKA», без «niedostępny» |
| Карточка BUFF: «Итого 85,35 < Цена 96,99» — ошибка | Не ошибка: в базе «Цена товара» — до кода, «Итого» — после кода с доставкой. То же для Ninja AF180 |
| Удалить пустую строку | По правилу пользователя ничего не удаляем: строка переименована и в архиве |

## Подтверждено

- Simond MT500 Warm: «89,99 zł», «Zalecana temperatura: 4 °C Temp. graniczna: -1 °C»; цены APPDAYS у модели нет.
- Viking Windcross GWS: «109,99 zł», «-12%», минимум за 30 дней «124,99 zł», «Dostawa GRATIS».
- Viking Arbok GWS (8a.pl): «114,99 zł», «109,24 zł» с CRAZY, минимум «113,99 zł (-4%)». Фото посмотрены: тонкие гладкие чёрные стрейч, без липучки, Windstopper, сенсорные пальцы (`arbok-photos-22-11.png`).
- Mammut Astro Light SO (MMT): «289,00 zł», «Darmowa dostawa od 200 zł».
- x-kom UGREEN US264: «Cena: 17,90 zł», «Darmowa dostawa do salonu».
- XMUSIC XWS600K Swim (Media Expert): код BW2011-2611 до 26.11 23:59, «399,99 zł» до кода, минимум за 30 дней «349,97 zł», «Taniej o 149,98 zł» → 199,99 zł.
- HP Envy Photo 7231 (Media Expert): код BW2011-2211 до 22.11 23:59, «349,99 zł» до кода, «Taniej o 150,99 zł» → 199 zł.
- Lidl Philips EP1200/00: сейчас «1013,99zł»; 399 zł с 23.11 — по записи в базе.
- Dreame Pocket Pro не выгоден: на Ceneo 190476184 есть «306,77zł».
- Notino Galeria Katowicka: «ul. 3-go Maja 30, parter 40-097 Katowice»; самовывоз «Nasze sklepy — Za darmo», доставка 8,90 zł.
- По базе: пустая строка, 2 дубликата, Douglas и Anker не найдены в Sovendus, 2 аватара InPost, 6 карточек Google дают Сердца, 17 меток «суперскидки-2026» (в нашем README ошибочно было 10), Sovendus: «Black Friday до 30.11.2026», устаревшие цифры в `final-selection.md`, порог Martes 149,99 zł в приложении, 11 приватных ссылок chatgpt.com/library в публичном репозитории.

## Не проверял сам

Рыночные цены для снятия метки с eufy E28, SteelSeries, Mac mini, ASUS ZenScreen, Philips 65MLED920, EP2223/40; Roborock Qrevo 5AE и F25 ACE Pro; Anker 735 и другие находки на Amazon; цена Ant Design в USD и условия возврата; наличие размеров у перчаток.

## Что изменено в Notion

Структура:
- База «Находки и купоны» разделена: 115 товаров остались в «🛍️ Товары и находки», 353 купона, бонуса и акции перенесены в новую базу «🎟️ Купоны и программы». Значения полей при переносе сохранились (проверено запросом).
- В товары добавлены поля: «Позиция покупки», «Роль», «Куплено», «Мин. 30 дн.», «Мин. рынка», «Фото» и формулы «Скидка к 30 дн. %», «Скидка к рынку %». В купоны: «География», «На уценку». Связь «Купон» ↔ «Товары».
- 10 представлений товаров переделаны: К покупке, Корзины по магазинам, Куплено, Суперскидки, Архив и кандидаты, Все варианты по позициям, Все товары, Нужно уточнить, Скоро истекают, Последние проверки. У купонов: Актуальные купоны (онлайн и Катовице), Скоро истекают, Архив купонов и другие города.
- Главная страница переписана как сводка (статус 5 покупок, сроки, ссылки), встроенная копия базы убрана, добавлены два встроенных представления.
- Страницы «Требования и метод поиска» и «Карта источников» объединены в «Справочник: размеры, правила и источники». Шесть страниц по датам (включая «По 2 варианта» и задание для Codex) перенесены в «Архив отчётов 20–22.11», ничего не удалено.

Отступления от отчёта:
- Поля не удалялись и тип «Магазин» не менялся на список: это стёрло бы данные. «Итого» оставлено числом, формулы скидки добавлены отдельно.
- Статусы не переименовывались (Проверено / Уточнить / Закончилась / Использовано / Архив).
- Фен: качественный вариант оставлен на Amazon (527,69, реальная скидка), Notino — запасной без Amazon (593,10). Основание отчёта для замены не подтвердилось.
- Второй светло-серый BUFF — 8a.pl с кодом T-Mobile (94,84), Sportano — запасной.

Строки:
- Архив: пустая строка, 2 дубликата, Sovendus Douglas и Anker, 2 аватара InPost, Dreame Pocket Pro, 55 офлайн-предложений только для других городов (География = «Другой город»).
- Вид «Бонус за баллы» для 6 заданий Google в T-Mobile.
- «Мин. покупка» заполнена у 14 купонов T-Mobile по тексту условий (в т. ч. Martes 250).
- «Действует до» = 30.11.2026 у 24 активных предложений Sovendus (окно выбора на витрине; срок конкретного кода не проверен).
- Роли и позиции у всех вариантов пяти покупок; «Куплено» у чёрного BUFF; новые строки: BUFF светло-серый 8a.pl и Sportano, Viking Arbok GWS, XMUSIC Swim, Roborock Qrevo 5AE, Roborock F25 ACE Pro, Anker 735.
- Суперскидки: метка снята с 7 позиций, добавлена EP1200/00; MG Home возвращён в товары.

Сегодня в 23:59 заканчиваются коды HP Envy и Braun: завтра их строки нужно перевести в «Закончилась».

## Дополнение 22.11 вечером: сверка полноты

Пользователь спросил, всё ли из отчёта и из второго списка второй модели («Собрал всё найденное в один список») попало в Notion. Не всё. Ниже — что добавлено после сверки. Цены открыты в браузере 22.11 около 19:15, если не сказано иное.

Не было в Notion и добавлено в «Товары и находки»:
- Находки второй модели, проверенные сейчас: Columbia Powder Lite (Modivo, 324,99 при минимуме 649,99; −10% DEALS2026 только от 2 вещей, до 22.11 22:59), Fire TV Stick HD (93,99 / 279,99), Kindle Colorsoft (709,99 / 1299,99), Echo Dot (180,99 / 409,99), Anker Nano 10000 (129 / 211,11), eufy P2 Pro (149 / 230,49), eufy E30 (204 / 294,29) — с меткой «Суперскидка». UGREEN Nexode 65 W (79,99 / 99,99, −20%), Govee (249,99 / 332,70), подставка UGREEN (37,40 / 50,48), Logitech MX Vertical (207,99, без строки минимума), OneBlade 360 Face (117,34), Apple USB-C 240 W 2 м (79,99) — без метки.
- Опровергнуто и сразу в архив с причиной: Tefal OptiGrill GC7128 (359 с кодом при минимуме 335,08 — вторая модель писала 559,99 и −36%), Roborock Saros 20 (Media Expert 3199 при минимуме 2892,40 — вторая модель писала 3099), INIU 20000 (93,30 / 98,22), Anker MagGo (189,05 / 199). Timberland 6 In Premium — «Ten produkt jest obecnie niedostępny».
- Мои находки 21.11 из `research-deals.json`, которые не дошли до Notion (32 строки, вместе с Columbia Powder Lite выше): перепроверены сегодня Peakfreak, PossibleCooker, Guerlain, Silver Monkey, Azzaro, Tom Ford, HyperX, NB BB550, Quiksilver, Armani, Beyerdynamic, Tefal Pure Tex, Hot Wheels, Astro A10, Alpinus, Tommy Jeans, Merrell Moab Speed 2 — цены совпали. Lidl KW48 (топпер, пылесос, аэрогриль, Tom Tailor, Remington, Parkside, Russell Hobbs), Mega Bloks, Merrell Agility Peak 6 / Trail, LEGO Botanicals, Melitta, BUFF Midweight — по данным 21.11, статус «Уточнить».
- Метка «Суперскидка» не ставилась, если скидка к рынку меньше 25% (Peakfreak −6%, PossibleCooker −11%, Pure Tex −6%, Agility Peak −20%) или к минимуму за 30 дней меньше 30%.
- Перчатки из `research-gloves-thin.json`, о которых писал отчёт: Salomon Cross Warm, Nike Sphere 4.0 мужские и женские (Martes, роль «Запасной», данные 21.11).

Исправлено в существующих строках:
- Roborock Qrevo 5AE: в базе уже была карточка Media Expert, я добавил дубль. Дубль в архиве, метка «Суперскидка» и минимум за 30 дней 1249,99 перенесены в исходную карточку.
- Anker 735: проверено, «Najniższa cena z 30 dni przed obniżką: 115,00 zł».
- Ant Design Q1 V2: в карточке было «~75 кодов», в `research-antdesign.md` проверено 44. Исправлено. Условия возврата проверены на antdesign.com/policies/refund-policy: 30 дней, только в нераспечатанной упаковке, обратная доставка и пошлины за счёт покупателя, возврат в Валенсию. «Бесплатная доставка от 79 USD» и «регулярная цена 35 USD» из отчёта не подтвердил.
- BaByliss Excess-HQ: добавлено утверждение отчёта о потоке 75 против 83 м³/ч у Caruso (не проверял).
- BUFF светло-серый: добавлена ловушка Allegro из отчёта (лот «Light Grey» за 88 zł в параметрах Solid Grey).
- Купоны: «Мин. покупка» 199 у Clarins и Wiejska Zagroda (было 14 из 16 строк отчёта). Названия магазинов: Samsung Polska → Samsung (3), RTV EURO AGD → RTV Euro AGD, T-Mobile Polska → T-Mobile (2), MMT Sklep Górski → MMT (2), Lidl.pl → Lidl. География «Катовице и Силезия» у 5 ресторанов (Taj, BUŁKĘS, Aleje Smaku, KATO Ramen, Współwinni).
- Главная страница: сроки 22.11 22:59 (Modivo), 23.11 и 26–29.11 (Lidl, x-kom), раздел «Личные купоны и баллы: на что тратить» по таблице отчёта с исправлением про Notino.

Уже было в Notion (проверено запросом): все подписки, доставка еды и рестораны из третьего и четвёртого разделов второго списка (активны), Lidl Nutella и Wedel, Kaufland Costa d'Oro и Coccolino, Tchibo −30%; подарок Friser от 250 zł, отзыв о швах Windcross, цена Mammut 215 zł в августе.

Не добавлял:
- Fire TV Stick 4K, Anker PowerCore 737, Soundcore Q30, Anker Nano 100 W из подборки ThinkApple — во втором списке нет ссылок. Добавлены позже, см. следующий раздел.
- Sklep Biegacza BUFF чёрный 99,99 — второй чёрный не нужен, и он дороже 8a.pl с кодом.
- CentrumRowerowe BUFF светло-серый 99,99 — сам отчёт пишет «конфигурация недоступна», ссылки нет.
- CEP Core Run 102,15 — перчатки отклонены, цену не проверял.
- 11 ссылок chatgpt.com/library в Notion оставлены: пространство личное, удалены только из публичного репозитория.

## Повторная сверка 22.11, 21:50

Пользователь прислал тот же второй список ещё раз с просьбой обновить Notion. Каждый пункт сверен SQL-запросом с обеими базами: 173 строки в «Товары и находки» и 33 карточки купонов по ссылкам из списка, плюс поиск Nutella, Wedel, Kaufland, Tchibo. Все пункты, кроме перечисленных ниже, уже были в базе. Taj: в условиях T-Mobile есть адрес «Katowice, ul. Dworcowa 4», география «Катовице и Силезия» верна.

Добавлено (ссылки взяты со страницы ThinkApple, цены открыты на Amazon.pl в 21:50, метка «Суперскидка»):
- Fire TV Stick 4K, B0GSH6FCBN: 134,99 при минимуме за 30 дней 319,99 (−58%), продавец Amazon, оценка 3,7/5 (929).
- soundcore Q30, B08Q89DN6V: 179,00 / 349,00 (−49%), AnkerDirect, 4,4/5.
- Anker PowerCore 737, B09VPHVT2Z: 284,05 / 669,00 (−58%), AnkerDirect, 4,4/5 (17 530).
- Anker Nano 100 W + кабель 1,8 м, B0G2BT36JK: 75,05 / 138,00 (−46%), AnkerDirect, 4,8/5 (219). Кабель 1,8 м, для позиции «кабель 1,5 м» не подходит.

Переведено в архив:
- Roborock F25 ACE Pro, Media Expert: 899,99 zł, на странице только «Sugerowana cena producenta: 1 299 zł», строки минимума за 30 дней нет, то есть цену не снижали. Только самовывоз в выбранных магазинах. К рынку около −10%.

## Третий список второй модели («свежая сводка подтверждённых скидок»), 22.11 22:00–22:20

Пользователь попросил внести список в Notion и разрешил: что не удаётся проверить — вносить с данными из документа. Такие строки в Notion со статусом «Уточнить» и пометкой «по отчёту второй модели, не проверял». SQL-лимит Notion закончился в 22:10, поэтому сверка новых строк с базой шла по запросу, сделанному до этого (поиск по названиям магазинов и сервисов в купонах).

Проверено в браузере и внесено как «Проверено»:
- Proton VPN Plus: «Billed at PLN 89.88 for the first 12 months, then renews at PLN 209.88» — −57% к продлению.
- Proton Unlimited: 195,48 zł, продление 299,88 zł — −35% к продлению. Вторая модель писала −50% от 389,88 (это 12 × помесячная цена).
- Proton Pass Plus 59,88 (продление 89,88, −33%), Family 83,88 (продление 149,88, −44%). «60% OFF» — от помесячной цены.
- NordVPN Basic: «1014,93 zł 253,53 zł za pierwsze 27 mies.», «Oszczędzasz 75%».
- Adobe Creative Cloud Pro: для Польши цены в евро, «80,61 € / mies.» → «32,24 € / mies.», «Zaoszczędź 60%», до 27.11. Цифры второй модели в долларах — не для Польши.
- Disney+: 16,99 / 23,99 / 39,99 zł на 3 месяца, «do 24 listopada».
- PlayStation Plus Premium: «Taniej o 33% przez 12 mies. Następnie 630,00 zł», до 30.11.
- Hebe онлайн: код POLSKIE «do −40% przy zakupach za min. 119 zł», BLACK20 −20% от 99 zł, второй товар за 1 zł у выбранных брендов. Акцию «второй товар −80% до 23:59» на главной не нашёл.
- OPPO Reno 15 Pro 12/512 коричневый, MediaMarkt: «Najniższa cena: 3499» → 2399 zł (−31%), метка «Суперскидка».
- Merrell Agility Peak 6 (699 → 329, размеры 41–47) и Agility Trail (419 → 199, размеры 40–50): статус «Проверено».

Проверено частично, статус «Уточнить»: Surfshark (8,99 zł/мес + 3 месяца; One по цене Starter не подтвердил), Internxt (баннер −87%, цены не разобрал), Skylum (баннер до −77%), TradingView (акции 22.11 ещё нет), SilverCrest Monsieur Cuisine Smart (на lidl.pl сейчас 2499, 1499 — с 23.11 по документу).

Не подтвердилось или уже было опровергнуто:
- Tefal OptiGrill «−36%» — документ повторяет; с кодом 359 при минимуме 335,08, в архиве.
- Roborock Saros 20 «3099 в 6 сетях» — на Ceneo минимум 3099 есть, но на Media Expert 3199 при минимуме за 30 дней 2892,40; остаётся в архиве, пояснение дописано.

Внесено по документу без проверки («Уточнить»): pCloud Lifetime, Microsoft 365 (сразу в архив — −16…−21%), Hebe в магазинах, Media Expert K-5309 и K-5311, RTV Euro AGD «второй товар −50%», Runnerinn BF15, Zara, Rossmann 1+1, Biedronka (ваучер 40 zł, Gallo, Prima, Gourmet Gold, Eduscho, MK Café, Kraina Wędlin), Lidl (масло Pilos, курица, фарш, Podwawelska, Gouda, молоко, одеяло Livarno), ALDI (Dallmayr, фарш, Kokett), 4F (ботинки и брюки, Flow Run Night Motion), OCHNIK и adidas Gazelle Bold на Zalando (Zalando не открылся в браузере).

Дополнены существующие строки: Keen (размеры, «Ostatnie sztuki», рынок ~390), Logitech MX Vertical (рынок 259), Kindle Colorsoft (Signature 859), Fire TV Stick 4K (Ceneo от 219), Roborock Qrevo 5AE (Euro 932,40 в рассрочку), x-kom (волна 23.11 в 08:00 в приложении), 8a.pl CRAZY. На главной странице календарь 23.11–09.12.

Уже было в Notion: HP Envy, Braun, Columbia Powder Lite, Philips EP1200, SEMST 1500, Airfryer XXL, Trust Yavi, XMUSIC, JLab, Fire TV HD, Kindle, Echo Dot, Anker 735, UGREEN Nexode, INIU, Anker 737, eufy E30 и P2 Pro, OneBlade, LG 65QNED72B6B, Parkside, Remington, Tom Tailor, Quiksilver, Keen, Merrell, Prime Video, Nutella, Nivea, Frisco.


## Четвёртый список второй модели (AI-подписки), 22.11 23:00–23:30

Перед внесением проверил дубли в купонах: ElevenReader Ultra, Picsart Pro, CampusAI (T-Mobile) и Adobe Creative Cloud Pro уже были. Новые 19 строк в «Купоны и программы» помечены ключевым словом BF2026.

Проверено в браузере, статус «Проверено»:
- ElevenLabs: «$99 for your first year, normally $220», «$445.50 for your first year, normally $990», до 01.12.
- Adobe Firefly (польский сайт, цены с VAT): Pro 11,35 € вместо 22,73 € на 6 месяцев, Pro Plus 22,72 € вместо 56,84 €, «Kończy się 6 gru».
- Grammarly Pro −50%, только первый период; дата окончания на странице не указана.
- TypingMind Lifetime Premium $79,20 вместо $198 с BLACKFRIDAY2026, «Ends November 30». Во втором отчёте срок 15.12 — неверно.
- MindPal: BLACKFRIDAY2026 до 11.12, Pro $187,20 за первый год вместо $468.
- Voibe: BFCM26 −25%, Lifetime $111,75 вместо $149. Во втором отчёте $149,25 вместо $199 — неверно.
- Higgsfield: годовые до −63% (Plus $33 вместо $59, Ultra $50 вместо $129). Срок этапа «23.11 02:00 CET» на странице не нашёл.
- Krea: годовые −70%, помесячные −25%.
- Kling: годовые −50%, помесячные −35% на 3 месяца (Standard $6,5 вместо $10).
- Topaz: Studio $299 вместо $499, Gigapixel $127 вместо $149, Video $254 вместо $299.
- Pictory −50% на все планы (кодов из отчёта на странице не видел), Fliki −50% с FLIKIBFCM50, InVideo до −75% (Max на 2 года).
- Hostinger VPS: до −69% (в отчёте −67%), от 23,99 zł/мес при оплате за 24 месяца, продление 51,99 zł/мес.
- Без скидок: ChatGPT, Claude (Pro €15/мес за год, €18 помесячно), Notion (до −20% за год), Perplexity. Runway — только −25% на Kling 4.0 до 30.11. Всё это одной строкой в архиве.

Не подтвердилось или неточно:
- Google AI Plus в Польше стоит 46,99 zł/мес, а не 23,99; Pro 97,99 zł/мес. Баннера скидки без входа в аккаунт нет — строка «Уточнить».
- Synthesia: баннера Black Friday нет, только обычная годовая цена (Starter $18 вместо $29) — «Уточнить».

По документу без проверки («Уточнить»): Magenta AI в Mój T-Mobile, Revolut ChatGPT Go (пресс-релиз Revolut 30.07.2026 условия подтверждает, в приложении не проверял), сроки Google AI (20–26.11 и 27.11), Higgsfield Market до 30.11, Hostinger до 14.12, Voibe до 30.11.

На главной в календарь добавлены 23.11 02:00 (Higgsfield), 27.11 (Google AI), 30.11 (TypingMind, Voibe, Runway), 01.12 (ElevenLabs), 06.12 (Firefly), 11.12 (MindPal), 14.12 (Hostinger). В справочник добавлен раздел о покупке подписок из Польши: VAT 23% к ценам в долларах, автопродление, серые ключи.


## Пятый список второй модели (Black Week, техника, куртки, подписки), 23.11

Перед внесением проверил дубли в обеих базах. Уже были: ASUS TUF A16 (x-kom), Sony WH-1000XM6 чёрные, TradingView, Disney+, Zara, APPDAYS, x-kom Black Weeks, Storytel и BookBeat через T-Mobile, PS Plus Premium, Hostinger VPS, Adobe CC Pro, ElevenLabs, Firefly, Krea, Topaz, Higgsfield. Новые строки помечены ключевыми словами BF2026 и «пятый список»: 24 в «Товары и находки» (16 «Проверено», 8 «Уточнить»), 20 в «Купоны и программы» (12 «Проверено», 8 «Уточнить»).

Проверено в браузере, статус «Проверено»:
- x-kom: HyperX OMEN 16 i7-14650HX RTX 5070 OLED 5 499 (минимум 6 499, «Obowiązuje do 30.11.2026», монитор HyperX OMEN 24 G2 за 1 zł); Acer Predator XB273UX2 549 (719); MSI MAG 275QF E20 499 (569); Dark Project ALU87A Fuji 199 (249); WD My Passport 2 TB 469 с black-weeks5, без кода 599 (559); Arctis Nova 7 Gen 2 479 с steelseries-bf, без кода 699 (519); Sony WH-1000XM6 тёмно-синие 1 299 (1 493).
- Media Expert: Motorola Edge 70 Fusion 12/256 + Moto Buds 2 1 799 с BW1311-0112 до 01.12 (1 999); Lenovo Idea Tab TB336FU 8/256 + стилус синий 899 с BW2011-2611 до 26.11 (999,99); TCL 75A400U 4 999 с BW2011-0112 до 01.12 (5 799,99); Huawei Watch GT 5 Active 46 мм 599 (799, так же на huawei.pl); Huawei Watch GT Runner 2 899,99 с BW1610-0112 до 01.12 (1 399).
- Komputronik: Huawei Watch D2 1 299 (1 459), Intel Core i9-14900K 2 099 (2 195,55); баннер «Black Weeks do -80%», «Raty 0%».
- Morele: «BLACK WEEKS DO -60%», «Raty 10x0%», выходная акция с BLACK26.
- Decathlon: Simond Alpinism −12 °C 499,99 (529,99), Quechua NH900 Warm −20 °C 499,99 (579,99).
- The North Face: «Uzyskaj wczesny dostęp. Zniżki do 40%». 4F Team: −30% от 300 zł. Answear: Magic Black Friday до −70%.
- TradingView: Essential −30% 469 zł, Plus −40% 934 zł, Premium −70% 938 zł, Ultimate −80% 2 143 zł — всё за 13 месяцев. Существующая строка обновлена до «Проверено».
- Storytel: 22,45 zł за 30 дней на 6 месяцев, потом 44,90. Netia: оптоволокно до 2 Гбит/с, 6 месяцев за 0 zł, пакеты с Prime и SkyShowtime. PlayStation Store и Xbox: игры до −80…−90%.
- Hostinger веб-хостинг: Premium 335,52 zł за 48 месяцев, продление 41,99 zł/мес; следующий план 479,52 zł (продление 72,99). ExpressVPN: Basic 66,92 € за 28 месяцев, Advanced 97,72 €. Krea: баннер «75% OFF».
- Trespass: Dorothea 200, Whitman II 355 — цены верны, но строки 30-дн. минимума нет, поэтому «Уточнить».

Не подтвердилось или неточно:
- ASUS TUF A16 R7-260 RTX 5060: на странице 5 499, а не 4 999 (минимум 7 799). Строка обновлена датой проверки.
- Silver Monkey X Control XL: на странице 59,99 без цены с кодом; 34,99 с black-weeks5 не видно.
- Simond Alpinism: в отчёте 539,96 с APPDAYS при минимуме 599,96, на сайте 499,99 при минимуме 529,99.
- Quechua NH900 Warm: в отчёте 244,98, на сайте 499,99.
- Canva Pro: в отчёте $10,83 вместо $12,99, на польской странице −50% на первые 3 месяца.
- Storytel: в отчёте «удлинённый пробный период», на сайте −50% на полгода.
- House: в отчёте до −40…−50%, на главной только «10% zniżki na zakupy online».
- Komputronik «30 rat 0% + 1 rata gratis» на главной не видел. Audioteka 8,95 zł не видел, только 14 дней бесплатно.
- PS5 Slim + 2 DualSense + GTA VI 3 799,99 и PS5 Digital + GTA VI 3 199,99 в Media Expert — цены верны, но комплекты новые и строки минимума нет.

Внесено по документу без проверки («Уточнить»): 50style (Reebok Glacier Shield 199,99, Ellesse Nebulus 279,99, Ellesse Hurricane 249,99, Nike W NSW Therma-FIT SNFL 399,99, Umbro Vela 132,99; сайт отвечает Access Denied), Zalando 4F −25% (каталог не открылся), Columbia PL до −50% (columbia.pl перенаправляет на американский сайт), Orange Motorola Signature 27 (на главной «prezenty o wartości 2400 zł», состав подарка не проверил), Huawei Watch GT 5 41 мм за 499 на huawei.pl, Netflix и HBO Max без акций, Steam 26–30.11, Hostido PROMPTOWY10 (сайт не загрузился), сроки Morele 29.11, TNF 24.11 08:00, Answear 02.12, Xbox 02.12, Hostinger 14.12.

Пропущено как уже записанное: x-kom «1 zł» в будни и +50 zł при самовывозе (есть строка x-kom Black Weeks), Disney+ до 24.11, Zara 26.11, Adobe CC Pro до 27.11, ElevenLabs, Firefly, Topaz, Higgsfield.

Прочие изменения 23.11:
- Статус «Закончилась» у строк, срок которых истёк 22.11: Braun Series 5, HP Envy Photo 7231, Ninja AF180, Philips NA229, Rituals (T-Mobile), Columbia Powder Lite.
- Lidl на lidl.pl: SilverCrest SEMST 1500 599 при минимуме 1 499 — «Проверено». Philips EP1200/00 онлайн 1 013,99, цены 399 на сайте нет. Monsieur Cuisine Smart всё ещё 2 499, 1 499 не видно. Обе строки остаются «Уточнить».
- На главной из календаря убраны прошедшие сроки 22.11; добавлены 24.11 08:00 (TNF), 24.11 (HBO Max), 26.11 (Lenovo, Steam), 29.11 (Morele), 30.11 (OMEN, BookBeat, Komputronik, PS Store, Steam), 01.12 23:59 (коды Media Expert), 02.12 (Answear, Xbox), 14.12 (веб-хостинг Hostinger).
