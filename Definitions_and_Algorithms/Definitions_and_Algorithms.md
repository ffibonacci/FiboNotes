## Полезные аббревиатуры и понятия

[**API**](https://ru.wikipedia.org/wiki/API) (Application Programming Interface/программный интерфейс приложения) — описание способов (набор классов, процедур, функций, структур или констант), которыми одна компьютерная программа может взаимодействовать с другой программой. Обычно входит в описание какого-либо интернет-протокола (например, RFC), программного каркаса (фреймворка) или стандарта вызовов функций операционной системы. Часто реализуется отдельной программной библиотекой или сервисом операционной системы. Используется программистами при написании всевозможных приложений. ([более детально](https://habr.com/ru/post/464261/))

[**TCP**](https://ru.wikipedia.org/wiki/Transmission_Control_Protocol) (Transmission Control Protocol/протокол управления передачей) — один из основных [протоколов передачи данных](https://ru.wikipedia.org/wiki/Протокол_передачи_данных) интернета, предназначенный для управления [передачей данных](https://ru.wikipedia.org/wiki/Передача_данных). Пакеты в TCP называются *сегментами*. В [стеке протоколов TCP/IP](https://ru.wikipedia.org/wiki/Список_интернет-протоколов_транспортного_уровня) выполняет функции [транспортного уровня](https://ru.wikipedia.org/wiki/Транспортный_уровень) [модели OSI](https://ru.wikipedia.org/wiki/Сетевая_модель_OSI).

[**DNS**](https://ru.wikipedia.org/wiki/DNS) (Domain Name System/система доменных имён) — компьютерная [распределённая система](https://ru.wikipedia.org/wiki/Распределённая_база_данных) для получения информации о [доменах](https://ru.wikipedia.org/wiki/Доменное_имя). Чаще всего используется для получения [IP-адреса](https://ru.wikipedia.org/wiki/IP-адрес) по имени [хоста](https://ru.wikipedia.org/wiki/Хост) (компьютера или устройства), получения информации о маршрутизации почты и/или обслуживающих узлах для протоколов в домене ([SRV-запись](https://ru.wikipedia.org/wiki/SRV-запись)).

[**Передача зоны DNS**, **AXFR**](https://ru.m.wikipedia.org/wiki/Передача_зоны_DNS) — вид [транзакции](https://ru.m.wikipedia.org/wiki/Транзакция_(информатика)) DNS. Является одним из механизмов [репликации](https://ru.m.wikipedia.org/wiki/Репликация_(вычислительная_техника)) [баз](https://ru.m.wikipedia.org/wiki/База_данных) DNS между серверами. 

[**SNI**](https://ru.wikipedia.org/wiki/Server_Name_Indication) (Server Name Indication/идентификация имен сервера) — расширение компьютерного протокола [TLS](https://ru.wikipedia.org/wiki/TLS), которое позволяет клиентам сообщать имя хоста, с которым он желает соединиться во время процесса «рукопожатия».

[**SSH**](https://ru.wikipedia.org/wiki/SSH) (Secure Shell/«безопасная оболочка») — [сетевой протокол прикладного уровня](https://ru.wikipedia.org/wiki/Протоколы_прикладного_уровня), позволяющий производить удалённое управление [операционной системой](https://ru.wikipedia.org/wiki/Операционная_система) и [туннелирование](https://ru.wikipedia.org/wiki/Туннелирование_(компьютерные_сети)) [TCP](https://ru.wikipedia.org/wiki/TCP)-соединений (например, для передачи файлов). Схож по функциональности с протоколами [Telnet](https://ru.wikipedia.org/wiki/Telnet) и [rlogin](https://ru.wikipedia.org/wiki/Rlogin), но, в отличие от них, [шифрует](https://ru.wikipedia.org/wiki/Шифрование) весь трафик, включая и передаваемые [пароли](https://ru.wikipedia.org/wiki/Пароль). SSH допускает выбор различных алгоритмов шифрования. SSH-клиенты и SSH-серверы доступны для большинства сетевых операционных систем.

[**DoS**](https://ru.wikipedia.org/wiki/DoS-атака) (Denial of Service/«отказ в обслуживании») — хакерская атака на вычислительную систему с целью довести её до отказа, то есть создание таких условий, при которых пользователи системы не смогут получить доступ к предоставляемым системным ресурсам (серверам), либо этот доступ будет затруднён. Отказ «вражеской» системы может быть и шагом к овладению системой (если в нештатной ситуации ПО выдаёт какую-либо критическую информацию — например, версию, часть программного кода и т. д.). Но чаще это мера экономического давления: потеря простой службы, приносящей доход, счета от провайдера и меры по уходу от атаки ощутимо бьют «цель» по карману. В настоящее время DoS и DDoS-атаки наиболее популярны, так как позволяют довести до отказа практически любую систему, не оставляя юридически значимых улик.

[**PGP**](https://ru.wikipedia.org/wiki/PGP) (Pretty Good Privacy) — компьютерная программа, также библиотека функций, позволяющая выполнять операции шифрования и цифровой подписи сообщений, файлов и другой информации, представленной в электронном виде, в том числе прозрачное шифрование данных на запоминающих устройствах, например, на жёстком диске.

[**SSL**](https://ru.wikipedia.org/wiki/SSL) (Secure Sockets Layer/слой защищённых [сокетов](https://ru.wikipedia.org/wiki/Сокет_(программный_интерфейс))) — [криптографический протокол](https://ru.wikipedia.org/wiki/Криптографический_протокол), который подразумевает более безопасную связь. Он использует асимметричную криптографию для аутентификации ключей обмена, симметричное шифрование для сохранения конфиденциальности, коды аутентификации сообщений для целостности сообщений. Протокол широко использовался для обмена мгновенными сообщениями и передачи голоса через [IP](https://ru.wikipedia.org/wiki/IP) (*Voice over IP* — [VoIP](https://ru.wikipedia.org/wiki/VoIP)) в таких приложениях, как [электронная почта](https://ru.wikipedia.org/wiki/Электронная_почта), интернет-факс и др. Устарел, теперь используется TLS.

[**TLS**](https://ru.wikipedia.org/wiki/TLS) (Transport layer security/Протокол защиты транспортного уровня), как и его предшественник SSL — [криптографические протоколы](https://ru.wikipedia.org/wiki/Криптографический_протокол), обеспечивающие защищённую передачу данных между узлами в сети Интернет. TLS и SSL используют [асимметричное шифрование](https://ru.wikipedia.org/wiki/Асимметричная_криптография) для аутентификации, [симметричное шифрование](https://ru.wikipedia.org/wiki/Симметричные_криптосистемы) для конфиденциальности и [коды аутентичности сообщений](https://ru.wikipedia.org/wiki/Имитовставка) для сохранения целостности сообщений.


## Методы и Алгоритмы

[**Вероятностная схема подписи Рабина**](https://ru.m.wikipedia.org/wiki/Вероятностная_схема_подписи_Рабина) — метод [цифровой подписи](https://ru.m.wikipedia.org/wiki/Цифровая_подпись) 

[**Преиму́щество двух слоно́в**](https://ru.m.wikipedia.org/wiki/Преимущество_двух_слонов) — позиционное преимущество наличия у одной из сторон двух слонов, а у другой — слона и коня или двух коней.

[**Криптография на основе эллиптических кривых**](https://habr.com/ru/company/qrator/blog/474832/), [эллиптические кривые](https://ru.wikipedia.org/wiki/Эллиптическая_кривая)

[**Код Хэ́мминга**](https://ru.wikipedia.org/wiki/Код_Хэмминга) — самоконтролирующийся и самокорректирующийся код. Построен применительно к [двоичной системе счисления](https://ru.wikipedia.org/wiki/Двоичная_система_счисления). Позволяет исправлять одиночную ошибку (ошибка в одном бите слова) и находить двойную.

[**Задача о рюкзаке** (**задача о ранце**)](https://ru.wikipedia.org/wiki/Задача_о_рюкзаке) — [NP-полная задача](https://ru.wikipedia.org/wiki/NP-полная_задача) [комбинаторной оптимизации](https://ru.wikipedia.org/wiki/Комбинаторная_оптимизация). Своё название получила от конечной цели: уложить как можно большее число ценных вещей в рюкзак при условии, что вместимость рюкзака ограничена. 

[**Схема Эль-Гамаля** (Elgamal)](https://ru.m.wikipedia.org/wiki/Схема_Эль-Гамаля) — [криптосистема](https://ru.m.wikipedia.org/wiki/Криптосистема) с открытым ключом, основанная на трудности вычисления [дискретных логарифмов](https://ru.m.wikipedia.org/wiki/Дискретный_логарифм) в [конечном поле](https://ru.m.wikipedia.org/wiki/Конечное_поле). Криптосистема включает в себя алгоритм шифрования и алгоритм цифровой подписи. Схема Эль-Гамаля лежит в основе бывших стандартов [электронной цифровой подписи](https://ru.m.wikipedia.org/wiki/Электронная_цифровая_подпись) в США ([DSA](https://ru.m.wikipedia.org/wiki/DSA)) и России ([ГОСТ Р 34.10-94](https://ru.m.wikipedia.org/wiki/ГОСТ_Р_34.10-94)).

[**Гипотеза математической вселенной**](https://ru.wikipedia.org/wiki/Гипотеза_математической_вселенной) (ГМВ, также известна как *Конечный Ансамбль*) — в физике и космологии, одна из гипотез «[теории всего](https://ru.wikipedia.org/wiki/Теория_всего)», предложенная физиком-теоретиком [Максом Тегмарком](https://ru.wikipedia.org/wiki/Тегмарк,_Макс).

[**Схема Шнорра**](https://ru.m.wikipedia.org/wiki/Схема_Шнорра) — одна из наиболее эффективных и теоретически обоснованных схем аутентификации. Безопасность схемы основывается на трудности вычисления [дискретных логарифмов](https://ru.m.wikipedia.org/wiki/Дискретный_логарифм). Предложенная Клаусом Шнорром схема является модификацией схем [Эль-Гамаля (1985)](https://ru.m.wikipedia.org/wiki/Схема_Эль-Гамаля) и [Фиата-Шамира (1986)](https://ru.m.wikipedia.org/wiki/Протокол_Фиата_—_Шамира), но имеет меньший размер подписи.