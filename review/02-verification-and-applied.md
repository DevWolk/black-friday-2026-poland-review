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

