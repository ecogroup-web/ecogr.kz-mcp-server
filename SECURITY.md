# Security policy

**English** · [Русский](#ru) · [Қазақша](#kk)

## Reporting a vulnerability

**Do not open a public issue** for a security problem.

Use GitHub private reporting: open the [Security tab](https://github.com/ecogroup-web/ecogr.kz-mcp-server/security/advisories/new) of this repository and press **Report a vulnerability**. Only the maintainers see the report.

Include: what you found, the tool or endpoint (`https://ecogr.kz/mcp`), steps to reproduce, and the impact. Remove tokens and personal data of other people from the report.

We aim to acknowledge a report within a few working days. Please give us reasonable time to fix the problem before you disclose it.

### In scope

- Access to data or actions the account behind the token is not allowed to have (another client's prices, orders or drafts; manager actions with a client token).
- Bypassing the token check, the `Origin` check or the rate limits.
- Submitting an order or a reserve through the server (it must never happen: a human always confirms on the site).
- Leaking tokens, personal or tax data in responses or logs.

### Out of scope

- Problems with orders, prices or accounts: contact your manager.
- Automated scanning that generates heavy traffic, denial of service, social engineering.
- Reports without a security impact (use a regular [issue](../../issues/new/choose)).

## If your token may have leaked

Open `https://ecogr.kz/mcp-server` and press **Reissue**: the old token stops working immediately. **Disconnect** deletes the token.

---

<a id="ru"></a>

[English](#security-policy) · **Русский** · [Қазақша](#kk)

# Политика безопасности

## Как сообщить об уязвимости

**Не создавайте публичное обращение (issue)** по проблеме безопасности.

Используйте приватное сообщение GitHub: откройте [вкладку Security](https://github.com/ecogroup-web/ecogr.kz-mcp-server/security/advisories/new) этого репозитория и нажмите **Report a vulnerability**. Сообщение увидят только мейнтейнеры.

Укажите: что Вы нашли, инструмент или адрес (`https://ecogr.kz/mcp`), шаги воспроизведения и последствия. Уберите из сообщения токены и персональные данные других людей.

Мы стараемся подтвердить получение в течение нескольких рабочих дней. Дайте разумное время на исправление, прежде чем раскрывать проблему.

### В рамках политики

- Доступ к данным или действиям, которых нет у аккаунта владельца токена (цены, заказы или черновики чужого клиента; действия менеджера с токеном клиента).
- Обход проверки токена, проверки `Origin` или лимитов запросов.
- Отправка заказа или резерва через сервер (этого быть не должно: человек всегда подтверждает на сайте).
- Утечка токенов, персональных или налоговых данных в ответах или журналах.

### Вне рамок

- Проблемы с заказами, ценами и аккаунтами — к своему менеджеру.
- Автоматическое сканирование с большой нагрузкой, отказ в обслуживании, социальная инженерия.
- Сообщения без влияния на безопасность (создайте обычное [обращение](../../issues/new/choose)).

## Если токен мог утечь

Откройте `https://ecogr.kz/mcp-server` и нажмите **«Перевыпустить»**: старый токен перестанет работать сразу. **«Отключить»** удаляет токен.

---

<a id="kk"></a>

[English](#security-policy) · [Русский](#ru) · **Қазақша**

# Қауіпсіздік саясаты

## Осалдық туралы қалай хабарлау керек

Қауіпсіздік мәселесі бойынша **жария хабарлама (issue) ашпаңыз**.

GitHub жеке хабарлау функциясын пайдаланыңыз: осы репозиторийдің [Security қойындысын](https://github.com/ecogroup-web/ecogr.kz-mcp-server/security/advisories/new) ашып, **Report a vulnerability** түймесін басыңыз. Хабарламаны тек мейнтейнерлер көреді.

Көрсетіңіз: не тапқаныңызды, құралды немесе мекенжайды (`https://ecogr.kz/mcp`), қайталау қадамдарын және салдарын. Хабарламадан токендер мен басқа адамдардың жеке деректерін алып тастаңыз.

Біз хабарламаны бірнеше жұмыс күні ішінде растауға тырысамыз. Мәселені ашпас бұрын түзетуге ақылға сыйымды уақыт беріңіз.

### Саясат аясында

- Токен иесінің аккаунтында жоқ деректерге немесе әрекеттерге қолжетімділік (бөтен клиенттің бағалары, тапсырыстары немесе жобалары; клиент токенімен менеджер әрекеттері).
- Токен тексеруін, `Origin` тексеруін немесе сұрау лимиттерін айналып өту.
- Сервер арқылы тапсырыс немесе резерв жіберу (бұлай болмауы тиіс: адам әрдайым сайтта растайды).
- Жауаптарда немесе журналдарда токендердің, жеке немесе салық деректерінің ағып кетуі.

### Саясаттан тыс

- Тапсырыстар, бағалар және аккаунттар мәселелері — менеджерге.
- Ауыр жүктеме тудыратын автоматты сканерлеу, қызмет көрсетуден бас тарту, әлеуметтік инженерия.
- Қауіпсіздікке әсері жоқ хабарламалар (кәдімгі [хабарлама](../../issues/new/choose) ашыңыз).

## Токен ағып кетуі мүмкін болса

`https://ecogr.kz/mcp-server` бетін ашып, **«Қайта шығару»** түймесін басыңыз: ескі токен бірден істен шығады. **«Өшіру»** токенді жояды.
