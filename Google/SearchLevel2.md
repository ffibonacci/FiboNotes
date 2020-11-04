#### Поиск по типу файла
`filetype:exe`

#### Поиск по расширению файла
`ext:exe`

#### Поиск на домене
`site:google.com`

### Фильтрация выдачи поиска
#### Поиск по url'у
`allinurl:https://typicalurl.com/common/main/eclipse.php`
##### Поиск в тексе помеченному как `<a name>`
`allinanchor: искомый_текст <a name>`
#### Поиск в заголовке страниц
`allintitle: искомый_текст`
#### Поиск в теге `body`
`allintext: искомый_текст`
### Время
`&tbs=qdr:y`, где 'y' это параметр: y=год, m=месяц, w=неделя, d=день, h=час, n=минута, s=секунда, 1=недавнее
#### Для поиска всего, что появилось за последнюю секунду
`искомый_текст &tbs=qdr:s`
#### Поиск в риал-тайме
`искомый_текст &tbs=qdr:1`
#### Задать временной промежуток
`искомый_текст daterange:2457024-2457205`
<br /> Можно использоваться чтобы перевести в нужный формат: http://www.onlineconversion.com/julian_date.htm
#### Поиск в разных странах
`искомый_текст gl=GE`, где GE - Германия

### Варианты выбора
`|`, логическое ИЛИ <br />
`""`, искать полное совпадение <br />
`-`, логическое НЕ <br />
`*`, используется как маска и означает ЧТО УГОДНО <br />

#### Примеры
`inurl:nasa.gov filetype:xlsx "address"` <br />
`allintext: card number expiration date /2020 cvv` <br />
`"DISTRIBUTION STATEMENT C" inurl:navy.mil` <br />
`allinurl:ftp:// verizon.net` <br />
`"pwd=" "UID=" ext:inc`, decrypt https://www.lab.artlung.com/ws-ftp-password-decoder/ <br />
`intext:DB_PASSWORD filetype:env`, search passwords in DataBases <br />
`filetype:reg HKEY_CURRENT_USER "Password"=`, search passwords in Windows Register <br />
`intitle: index of` <br />
`intitle:"Index of /Personal/" -names -tutorial -banking` <br />
`filetype:pcf vpn OR Group` <br />
