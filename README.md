<p align="center">
    <img alt="" src="https://habrastorage.org/webt/un/ke/6d/unke6dmjxotrhtuqkkmppy88hqy.jpeg" />
</p>

Библия QA это 200++ страниц обновляемой смеси ответов на вопросы с реальных собеседований на QA, перевода интересного контента с зарубежных ресурсов и агрегации материала с отечественных. Уже на начальной стадии имеет несколько тысяч уникальных просмотров репозитория и огромный положительный фидбэк от коммьюнити, что даёт некоторые гарантии для сомневающихся, доверять ли этому материалу или контрибьютить ли сюда.
<cut />

ВНИМАНИЕ! Для того, чтобы увидеть материал целиком, нужно открыть первую или вторую часть в файлах (Manual part 1 или 2). Пришлось их разбить ввиду ограничения на размер одного файла в 1 мб.

В первую очередь хочу подчеркнуть, что в данный момент этот материал от джуна – джунам, от intermediate – таким же, но будет полезен всем грейдам, тем более что часть материала далеко не начального уровня. Качество материала (особенно перевода) будет улучшаться по мере вычитки и вклада сообщества. 

Что касается источников и ресурсов, то список не полный. В первоначальном конспекте для себя я не сохранял ссылки, так что, если увидели авторский контент, прошу не ругаться, напишите - добавлю в источники. Список полезных ресурсов я не пытался сделать всеобъемлющим, а лишь указал те, что пригодились лично мне, на самом деле их в разы больше.

Также отмечу, что и сам материал пока что далеко не всеобъемлющий. Предполагается, что это некий гибрид ответов на вопросы и базовой теории и здесь темы раскрыты в той мере, что требуется на собеседовании. То есть ориентир и какая-то база есть, но при необходимости копаете дальше уже сами. Каждый термин, каждая тема представляется мне как трехмерный объект и не всегда можно достичь понимания, глядя в лоб (один источник). Порой требуется посмотреть под разными углами (в разных источниках).

Если есть что исправить или дополнить – пишите в tg @VA610/создавайте issue/форкайте и коммитьте! Любые замечания, любые запросы на недостающие темы постараюсь обработать как можно скорее!

# Оглавлениe

## Manual part 1

###  HR-часть

- Вопросы с реальных собеседований с этапа HR

###  Общее о тестировании
- Что означает тестирование ПО?
- Почему требуется тестирование ПО?
- Что означает обеспечение качества (Quality Assurance - QA) при тестировании ПО?
- Что означает контроль качества (Quality Control - QC) при тестировании ПО?
- Что означает качество ПО? (Software Quality)
- Объясните отличия в QA, QC и тестировании
- Что означает Verification при тестировании ПО?
- Что означает Validation в тестировании ПО?
- Разница между Design Verification и Design Validation?
- Принципы тестирования?
- Критерии выбора тестов?
- Что подразумевается под тестовым покрытием? (Test Coverage)
- Что такое модель зрелости тестирования (TMM - Test Maturity Model)?
- Что такое тестирование со сдвигом влево? (Shift left testing)
- Что такое независимое тестирование? (Independent testing)
- В чем разница между превентивным и реактивным подходами в тестировании? (Preventative and Reactive approaches)
- Перечислите типичные возможные обязанности инженера по обеспечению качества?
- Что такое аудит качества?
- Почему тестирование делится на отдельные этапы?
- Почему невозможно полностью протестировать ПО?
- Как вы тестируете продукт, если требования еще не зафиксированы?
- Как вы узнаете, было ли создано достаточно тестов для тестирования продукта?
- Как вы понимаете инспекцию?
- Какие есть роли/должности в команде?
- Опишите жизненный цикл продукта по этапам - какие участники на каждом этапе, какие у них роли? Какие артефакты на каждом этапе?
- Кто такой SDET?
- Что такое тестирование как сервис? (TaaS – testing as a Service)
- Что подразумевается под тестовой средой? (Test Environment/Test Bed)
- Что подразумевается под тестовыми данными?
- Основные фазы тестирования?
- Подробнее про бета-тестирование?
- Что означает пилотное тестирование? (Pilot)
- В чем отличие build от release?
- Что такое бизнес – логика (domain)?
- Ты – единственный тестировщик на проекте. Что делать?
- Основные инструменты тестировщика?

###  Виды тестирования

- Какие существуют основные виды тестирования ПО?
- Типы тестирования? (White/Black/Grey Box)
- Что означает тестирование черного ящика?
- Что означает тестирование белого ящика?
- Что означает тестирование серого ящика? (Grey box)
- Основные отличия White/grey/black box?
- Что такое деструктивное/разрушающее/негативное тестирование? (DT - Destructive testing)
- Что такое недеструктивное/неразрушающее/позитивное тестирование? (NDT – Non Destructive testing)
- Что такое пирамида/уровни тестирования? (Testing Levels)
- Что подразумевается под компонентным/модульным/юнит тестированием? (Component/Module/Unit testing)
- Что подразумевается под интеграционным тестированием? (Integration testing)
- Разница между Unit testing и Integration testing?
- Что такое системное интеграционное тестирование? (SIT - System Integration testing)
- Что подразумевается под инкрементальным подходом? (Incremental Approach)
- Что подразумевается под подходом снизу-вверх? (Bottom-Up Approach)
- Что подразумевается под подходом сверху-вниз? (Top-Down Approach)
- Что подразумевается под гибридным/сэндвич-подходом? (Sandwich Approach)
- Что подразумевается под подходом Большого взрыва?  (Big Bang Approach)
- В чем разница между тест-драйвером и тест-заглушкой? (Test Driver and Test Stub)
- Что подразумевается под системным тестированием?
- Можем ли мы провести системное тестирование на любом этапе?
- Что такое функциональное тестирование?
- Что такое тестирование совместимости/взаимодействия? (Compatibility/Interoperability testing)
- Что такое тестирование на соответствие? (Conformance/Compilance testing)
- Что такое нефункциональное тестирование?
- Основные понятия в тестировании производительности?
- Тестирование производительности клиентской части и серверной, в чем разница?
- В общем виде что такое тестирование производительности?
- Что такое тестирование емкости/способностей? (Capacity)
- Что означает тестирование масштабируемости? (Scalability)
- Разница между тестированием ёмкости/способностей и тестированием масштабируемости? (Capacity vs Scalability)
- Расскажите о стрессовом тестировании? (Stress testing)
- Расскажите о нагрузочном тестировании? (Load)
- Что такое объемное тестирование? (Volume testing)
- Тестирование выносливости/стабильности/надежности (Soak/Endurance/Stability/Reliability testing)
- Что такое спайк/шиповое тестирование? (Spike)
- Что такое тестирование устойчивости? (Resilence)
- Что такое тестирование времени отклика? (Response time testing)
- Что такое Ramp тестирование?
- Что такое тестирование хранилища? (Storage testing)
- Что такое тестирование на отказ и восстановление? (Failover and Recovery testing)
- Что вы знаете о Тестировании удобства пользования? (Usability testing)
- Отличия тестирование на удобство пользования и тестирования доступности? (Usability Vs. Accessibility testing)
- Что такое тестирование интерфейса? (UI testing)
- Что такое тестирование рабочего процесса/воркфлоу? (Workflow testing)
- Что вы знаете о пользовательском приемочном тестировании? (UAT – User Acceptance testing)
- Что такое эксплуатационное приемочное тестирование? (OAT - Operational Acceptance testing)
- Расскажите об инсталляционном тестировании?
- Что вы знаете о тестировании безопасности? (Security and Access Control testing)
- Что означает оценка уязвимости/защищенности? (Vulnerability Assessment)
- Расскажите подробнее о тестировании на проникновение? (Penetration testing)
- Отличия Vulnerability Assessment от Penetration testing?
- Что такое Fuzz тестирование?
- Можно ли отнести тестирование безопасности или нагрузочное тестирование к функциональным видам тестирования?
- Что вы знаете о конфигурационном тестировании? (Configuration testing)
- Что вы знаете про регрессионное тестирование? (Regression testing)
- Типы регрессии по Канеру?
- Что подразумевается под проверкой дыма/дымовым тестированием? (Smoke testing)
- Что такое тестирование встряхиванием? (Shake out testing)
- Что подразумевается под санитарным тестированием/согласованности/исправности? (Sanity testing)
- Отличие санитарного тестирования от дымового? (Sanity vs Smoke testing)
- В чем разница между повторным и регрессионным тестированием?
- Объясните, что такое тестирование N+1?
- Что означает подтверждающее тестирование? (confirmation/re-testing)
- Что вы знаете о тестировании сборки? (Build Verification Test)
- Что такое тестирование файлов cookie?
- Что такое тестирование потоков? (Thread testing)
- Что такое тестирование документации? (Documentation testing)
- Какие вы знаете уровни тестирования данных?
- Что такое подкожный тест? (Subcutaneous test)
- Расскажите о локализации, глобализации и интернационализации? (Localization/ globalization/internationalization testing)
- Что такое исследовательское тестирование? (Exploratory testing)
- Что вы знаете о турах Виттакера в исследовательском тестировании?
- Что такое Свободное или Интуитивное тестирование? (Adhoc)
- Что вы знаете о мутационном тестировании? (Mutation testing)
- Что означает механизм тестирования по ключевым словам? (Keyword Driven testing Framework)
- Что вы знаете о тестировании интерфейса прикладного программирования (API - Application Programming Interface)?
- Как протестировать API без документации/черным ящиком?
- А что такое endpoint?
- Frontend testing Vs. Backend testing?
- Что подразумевают под эталонным тестированием? (Baseline testing)
- В чем разница между Baseline и Benchmark testing?
- Что такое параллельное/многопользовательское тестирование? (Concurrency/Multi-user testing)
- Как вы думаете, что такое тестирование на переносимость?
- Что такое тестирование графического интерфейса/визуальное тестирование? (GUI - Graphical User Interface)
- Что такое A/B тестирование?
- Что означает сквозное тестирование? (E2E - End–to–End)
- В чем разница между E2E и системным тестированием?
- Что такое параллельное тестирование? (Parallel testing)

###  Тест дизайн
- Тест дизайн? (Test Design)
- Перечислите известные техники тест-дизайна?
- Что такое статическое тестирование, когда оно начинается и что оно охватывает?
- Что такое динамическое тестирование, когда оно начинается и что оно охватывает?
- Какие виды Review вы знаете?
- Что вы знаете о Data Flow testing?
- Что вы знаете о Control Flow testing?
- Что такое Loop coverage?
- Что такое Race coverage?
- Тестирование пути и тестирование базового пути? (Path testing & Basis Path testing)
- Что вы знаете о Statement coverage?
- Что вы знаете о Decision coverage?
- Что вы знаете о Branch coverage?
- Что вы знаете о Condition coverage?
- Что вы знаете о FSM coverage?
- Что такое Function coverage?
- Что такое Call coverage?
- Что означает LCSAJ coverage?
- Сравнение некоторых метрик
- Что такое Equivalence Partitioning?
- Что такое Boundary Value Analysis?
- Что такое Error Guessing?
- Что такое Cause/Effect?
- Что такое Exhaustive testing?
- Какие вы знаете комбинаторные техники тест-дизайна?
- Что такое тестирование ортогональных массивов? (OAT - Orthogonal Array testing)
- Что такое Domain analysis/testing?
- Что такое Cyclomatic Complexity в тестировании ПО?
- Что такое State Transition testing?
- Что такое Scenario (use case) testing?
- Что такое Decision Table testing?
- Что такое Random testing?
- Что такое Syntax testing?
- Что вы знаете о Classification tree method?
- Как мы узнаем, что код соответствует спецификациям?
- Что включает в себя матрица отслеживания требований? (RTM - Requirement Traceability Matrix)
- В чем разница между Test matrix и Traceability matrix?
- Что такое анализ GAP?
- Что такое граф причинно-следственных связей? (Cause Effect Graph)
- В чем разница между предугадыванием ошибок и посевом? (Error guessing and error seeding)
- Стили тестов?
- Техники тестирования требований?
- Что такое эвристики?

###  Тестовые артефакты и документация (Test Deliverables/TestWare/test artifacts)

- Виды тестовой документации?
- Какие отличия у тест-кейса высокого и низкого уровня?
- Отличия Test Suite от Test Scenario?
- Какие отличия у плана тестирования и стратегии тестирования?
- Виды тест планов?
- Что является основой для подготовки плана приемки? (PAP - Product Acceptance Plan)
- В чем разница между тест-кейсом и чек-листом?
- В чем разница между тест-кейсами высокого уровня и низкого уровня?
- Чем Test case отличается от сценария тестирования?
- Что такое тест-анализ/основа теста? (Test Analysis/Test Basis)
- Что такое документ бизнес-требований (BRD)?
- Что вы знаете о требованиях (уровни/виды и т. д.)?
- Рассажите, какие есть требования к самим требованиям?

### Дефекты и ошибки
- Что такое дефект?
- Классы дефектов?
- Какие есть категории дефектов?
- Error/Mistake/Defect/Bug/Failure/Fault?
- Каково содержание эффективного сообщения об ошибке?
- Несколько ключевых моментов, которые следует учитывать при написании отчета об ошибке?
- Серьезность и Приоритет Дефекта (Severity & Priority)
- Может ли быть высокий severity и низкий priority? А наоборот?
- Жизненный цикл дефекта?
- Пришёл баг из продакшена, что делаем?
- Что такое утечка дефектов и релиз бага? (Bug Leackage & Bug Release)
- Что означает плотность дефектов при тестировании ПО?
- Что означает процент обнаружения дефектов при тестировании ПО?
- Что означает эффективность устранения дефектов при тестировании ПО? (DRP)
- Что означает эффективность Test case в тестировании ПО? (TCE)
- Возраст дефекта в тестировании ПО?
- Что такое принцип Парето в тестировании ПО?
- Каковы различные способы применения принципа Парето в тестировании ПО?
- В чем основное отличие отладки от тестирования? (Debugging Vs. Testing)
- Почему в программном обеспечении есть ошибки?
- Что вы будете делать, если во время тестирования появится ошибка?
- Как вы справляетесь с невоспроизводимой ошибкой?
- Если продукт находится в производстве и один из его модулей обновляется, то необходимо ли провести повторную проверку?
- Что такое анализ рисков?
- В чем разница между coupling и cohesion?
- Что такое скрытый дефект? (Latent defect)
- Что такое маскировка ошибок, объясните примером?
- Категории отладки? (Debugging)
- Что такое Эффективность удаления дефектов? (DRE - Defect Removal Efficiency)
- Что такое сортировка дефектов? (Bug triage)

### SDLC и STLC
- Что вы знаете о жизненном цикле разработки ПО? (SDLC - Software Development Lifecycle)
- Что такое цикл/колесо Деминга? (Deming circle/cycle/wheel)
- Модели разработки ПО?
- Что такое Agile?
- Что такое Scrum?
- Какие вообще особенности у тестирования в Scrum?
- В чем отличие Kanban от Scrum?
- Что знаете о User stories в гибких подходах к разработке?
- Что значит жизненный цикл тестирования ПО? (STLC – Software Testing Lifecycle)
- Что вы знаете о техниках оценки теста? (Test Estimation)
- В чем разница между SDLC и STLC?
- Что такое быстрая разработка приложений? (RAD - Rapid Application Development)
- Что такое разработка через тестирование (TDD - Test Driven Development)?
- TDD в Agile Model Driven Development (AMDD)
- Тестирование на основе моделей (MDD - Model-driven Development)
- Тестирование на основе данных (DDT - Data Driven testing)
- Тестирование на основе риска (RBT - Risk Based Testing)
- Что вы знаете о потоковом тестировании? (BFT — BusinessFlowTesting)

### Тестирование в разных сферах/областях (testing different domains)
- Что такое веб-тестирование и как его производить?
- Тестирование банковского ПО
- Тестирование электронной коммерции (eCommerce)
- Тестирование платежного шлюза (Payment Gateway)
- Тестирование систем розничной торговли (POS - Point Of Sale)
- Тестирование в сфере страхования (Insurance)
- Тестирование в сфере телекоммуникаций (Telecom)
- Тестирование протокола: L2 и L3 OSI
- Тестирование интернета вещей (IoT - Internet of Things)
- Что такое облачное тестирование? (Cloud testing)
- Что такое тестирование сервис-ориентированной архитектуры? (SOA - Service Oriented Architecture)
- Что такое тестирование планирования ресурсов предприятия? (ERP - Enterprise Resource Planning)
- Тестирование качества видеосвязи WebRTC-based сервиса видеоконференций
- Что такое тестирование ETL?

### Мобильное тестирование

- Каковы особенности в тестировании мобильных приложений?
- В чем отличия тестирования мобильного приложения от десктопного?
- В чем отличия тестирования мобильного приложения от web?
- Почему так много внимания уделяется прерываниям? Что такое Activity Lifecycle?
- Что вы знаете о симуляторах и эмуляторах?
- Типы мобильных приложений?
- Что основное проверить при тестировании мобильного приложения?
- Как быть с покрытием девайсов?
- Последнее обновление Android/iOS, что нового?
- Основные различия iOS и Android?
- Виды жестов и т.п.?
- Как проверить использование процессора на мобильных устройствах?
- Объясните критические ошибки, с которыми вы сталкиваетесь при тестировании на мобильных устройствах или в приложениях?
- Что вы знаете о PWA?

###  Сети и около них
- Что такое http?
- Компоненты HTTP?
- Методы HTTP-запроса?
- Что такое ресурс?
- Что такое веб-сервис? (WS - Web service)
- Отличие сервиса от сервера?
- Отличие сервиса от веб-сайта?
- Что такое REST, SOAP? В чем отличия?
- Что такое JSON, XML?
- Коды ответов/состояния сервера с примерами? (HTTP status code)
- Почему ошибка 404 относится к 4** - клиентской, если по идее должна быть 5**?
- Какие еще бывают протоколы?
- TCP/IP это?
- Что такое куки (cookies)?
- Разница между cookie и сессией/сеансом?
- Отличие stateless и stateful?
- Различия методов GET и POST?
- Клиент - серверная архитектура?
- Уровни OSI?
- Что вы подразумеваете под потоковыми медиа? (Streaming media)
- Основные команды Linux?
- Почему важно тестировать в разных браузерах?
- Адаптивный веб-дизайн vs. Отзывчивый веб-дизайн, в чем разница? (Adaptive Vs. Responsive)
- Как сервер узнаёт, с какого типа устройства/браузера/ОС/языка вы открываете веб-сайт? (Например, для Adaptive design)
- Чем отличается авторизация от аутентификации?
- Как работает авторизация/аутентификация? Как сайт понимает, что ты залогинен?
- Почему важно делать подтверждение e-mail при регистрации?
- Что такое кэш и зачем его очищать при тестировании?
- Что такое AJAX в вебе?
- Как работает браузер (коротко)?
- Как работает сотовая связь?
- Как работает подключение к Wi-Fi?

### Базы данных
- Может ли у ПО быть сразу несколько баз данных?
- Что такое SQL?
- Что вы знаете о NoSQL?
- Что такое нормальные формы?
- Понятие хранимой процедуры?
- Понятие триггера?
- Что такое индексы? (Indexes)
- Какие шаги выполняет тестер при тестировании хранимых процедур?
- Как бы вы узнали для тестирования базы данных, сработал триггер или нет?
- Как тестировать загрузку данных при тестировании базы данных?
- Основные команды SQL?
- Подробнее о джойнах? (Join)
- Типы данных в SQL?

### ПРАКТИКА
- [Дана форма для регистрации. Протестируйте](docs/practice.md#Дана-форма-для-регистрации-Протестируйте)
- [Определение серьезности и приоритета](docs/practice.md#Определение-серьезности-и-приоритета)
- [Определение граничных значений и классов эквивалентности](docs/practice.md#Определение-граничных-значений-и-классов-эквивалентности)
- [Логические задачи](docs/practice.md#Логические-задачи)
- [Еще примеры](docs/practice.md#Еще-примеры)
- [Набор небольших задач по SQL](docs/practice.md#Набор-небольших-задач-по-sql)
- [Тестирование чашки для кофе](docs/practice.md#Тестирование-чашки-для-кофе)
- [HR: Как вы будете решать конфликты между членами вашей команды?](docs/practice.md#hr-Как-вы-будете-решать-конфликты-между-членами-вашей-команды)
- [HR: Что делать, если разработчик утверждает, что найденный дефект таковым не является?](docs/practice.md#hr-Что-делать-если-разработчик-утверждает-что-найденный-дефект-таковым-не-является)
- [Вот тебе комп и работающий сайт. Сделай мне 401-ю ошибку](docs/practice.md#Вот-тебе-комп-и-работающий-сайт-Сделай-мне-401-ю-ошибку)

### С чего начать абсолютному новичку?
- Путь
- CV
- Собеседование
- Ошибки в работе у начинающих тестировщиков

### [Полезное](docs/resources.md)
- [Youtube-каналы](docs/resources.md#youtube-каналы)
- [Telegram](docs/resources.md#telegram)
- [Web](docs/resources.md#web)
- [Книги](docs/resources.md#Книги)
- [Курсы](docs/resources.md#Курсы)

### [Источники](docs/sources.md)
