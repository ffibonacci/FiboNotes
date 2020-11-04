#### Search by file type
`filetype:exe`

#### Search by extension
`ext:exe`

#### Search on domain
`site:google.com`

#### Filter search
##### Search by url
`allinurl:https://typicalurl.com/common/main/eclipse.php`
##### Search in text marked as `<a name>`
`allinanchor: search this text in <a name>`
##### Search in page title
`allintitle: search this text in title`
##### Search in `body`
`allintext: search this text in body`
#### Time
`&tbs=qdr:y`, where 'y' is parameter: y=year,m=month, w=week, d=day, h=hour, n=minute, s=second, 1=most recent
##### To search everything appeared in last second
`search this text &tbs=qdr:s`
##### To search in real time
`search this text &tbs=qdr:1`
##### To set date range
`searchi this text daterange:2457024-2457205`
<br /> Use it to translate date: http://www.onlineconversion.com/julian_date.htm
#### Search in different countries
`search this in gl=GE`, where GE is Germany

#### Options
`|`, means logical OR <br />
`""`, means search full compliance <br />
`-`, means everything, but not <br />
`*`, using like mask and means whatever <br />

##### Examples
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
