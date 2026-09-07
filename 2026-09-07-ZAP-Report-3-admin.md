# ZAP by Checkmarx Scanning Report

ZAP by [Checkmarx](https://checkmarx.com/).


## Summary of Alerts

| Risk Level | Number of Alerts |
| --- | --- |
| High | 0 |
| Medium | 3 |
| Low | 7 |
| Informational | 7 |




## Insights

| Level | Reason | Site | Description | Statistic |
| --- | --- | --- | --- | --- |
| Low | Warning |  | ZAP warnings logged - see the zap.log file for details | 12    |
| Low | Exceeded High | https://tfctest-003-production.up.railway.app | Percentage of slow responses | 99 % |
| Info | Informational | http://tfctest-003-production.up.railway.app | Percentage of responses with status code 3xx | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Percentage of endpoints with content type text/plain | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Percentage of endpoints with method POST | 100 % |
| Info | Informational | https://clientservices.googleapis.com | Count of total endpoints | 1    |
| Info | Informational | https://clientservices.googleapis.com | Percentage of slow responses | 100 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of endpoints with content type application/x-protobuf | 33 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of endpoints with content type text/plain | 66 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of endpoints with method GET | 66 % |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of endpoints with method POST | 33 % |
| Info | Informational | https://content-autofill.googleapis.com | Count of total endpoints | 3    |
| Info | Informational | https://content-autofill.googleapis.com | Percentage of slow responses | 100 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of responses with status code 2xx | 33 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of responses with status code 3xx | 42 % |
| Info | Exceeded Low | https://tfctest-003-production.up.railway.app | Percentage of responses with status code 4xx | 6 % |
| Info | Exceeded Low | https://tfctest-003-production.up.railway.app | Percentage of responses with status code 5xx | 17 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with content type application/javascript | 31 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with content type text/css | 2 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with content type text/html | 7 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with content type text/plain | 2 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with content type text/x-component | 50 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with method GET | 86 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Percentage of endpoints with method POST | 13 % |
| Info | Informational | https://tfctest-003-production.up.railway.app | Count of total endpoints | 38    |
| Info | Informational | https://update.googleapis.com | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://update.googleapis.com | Percentage of endpoints with content type application/json | 100 % |
| Info | Informational | https://update.googleapis.com | Percentage of endpoints with method POST | 100 % |
| Info | Informational | https://update.googleapis.com | Count of total endpoints | 3    |
| Info | Informational | https://update.googleapis.com | Percentage of slow responses | 100 % |
| Info | Informational | https://zznkykduwjrefvxoiwkx.supabase.co | Percentage of responses with status code 2xx | 100 % |
| Info | Informational | https://zznkykduwjrefvxoiwkx.supabase.co | Percentage of endpoints with content type application/json | 50 % |
| Info | Informational | https://zznkykduwjrefvxoiwkx.supabase.co | Percentage of endpoints with method OPTIONS | 50 % |
| Info | Informational | https://zznkykduwjrefvxoiwkx.supabase.co | Percentage of endpoints with method POST | 50 % |
| Info | Informational | https://zznkykduwjrefvxoiwkx.supabase.co | Count of total endpoints | 2    |
| Info | Informational | https://zznkykduwjrefvxoiwkx.supabase.co | Percentage of slow responses | 100 % |







## Alerts

| Name | Risk Level | Number of Instances |
| --- | --- | --- |
| Content Security Policy (CSP) Header Not Set | Medium | 2 |
| Cross-Domain Misconfiguration | Medium | 1 |
| Missing Anti-clickjacking Header | Medium | 2 |
| Big Redirect Detected (Potential Sensitive Information Leak) | Low | 1 |
| Cookie with SameSite Attribute None | Low | 2 |
| Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s) | Low | 3 |
| Server Leaks Version Information via "Server" HTTP Response Header Field | Low | 1 |
| Strict-Transport-Security Header Not Set | Low | Systemic |
| Timestamp Disclosure - Unix | Low | 3 |
| X-Content-Type-Options Header Missing | Low | Systemic |
| Authentication Request Identified | Informational | 1 |
| Content-Type Header Missing | Informational | 1 |
| Loosely Scoped Cookie | Informational | 2 |
| Modern Web Application | Informational | 1 |
| Re-examine Cache-control Directives | Informational | 2 |
| Session Management Response Identified | Informational | 2 |
| User Agent Fuzzer | Informational | Systemic |




## Alert Detail



### [ Content Security Policy (CSP) Header Not Set ](https://www.zaproxy.org/docs/alerts/10038/)



##### Medium (High)

### Description

Content Security Policy (CSP) is an added layer of security that helps to detect and mitigate certain types of attacks, including Cross Site Scripting (XSS) and data injection attacks. These attacks are used for everything from data theft to site defacement or distribution of malware. CSP provides a set of standard HTTP headers that allow website owners to declare approved sources of content that browsers should be allowed to load on that page — covered types are JavaScript, CSS, HTML frames, fonts, images and embeddable objects such as Java applets, ActiveX, audio and video files.

* URL: https://tfctest-003-production.up.railway.app/
  * Node Name: `https://tfctest-003-production.up.railway.app/`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/admin
  * Node Name: `https://tfctest-003-production.up.railway.app/admin`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``


Instances: 2

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to set the Content-Security-Policy header.

### Reference


* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP)
* [ https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html ](https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html)
* [ https://www.w3.org/TR/CSP/ ](https://www.w3.org/TR/CSP/)
* [ https://w3c.github.io/webappsec-csp/ ](https://w3c.github.io/webappsec-csp/)
* [ https://web.dev/articles/csp ](https://web.dev/articles/csp)
* [ https://caniuse.com/#feat=contentsecuritypolicy ](https://caniuse.com/#feat=contentsecuritypolicy)
* [ https://content-security-policy.com/ ](https://content-security-policy.com/)


#### CWE Id: [ 693 ](https://cwe.mitre.org/data/definitions/693.html)


#### WASC Id: 15

#### Source ID: 3

### [ Cross-Domain Misconfiguration ](https://www.zaproxy.org/docs/alerts/10098/)



##### Medium (Medium)

### Description

Web browser data loading may be possible, due to a Cross Origin Resource Sharing (CORS) misconfiguration on the web server.

* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)`
  * Method: `OPTIONS`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`


Instances: 1

### Solution

Ensure that sensitive data is not available in an unauthenticated manner (using IP address white-listing, for instance).
Configure the "Access-Control-Allow-Origin" HTTP header to a more restrictive set of domains, or remove all CORS headers entirely, to allow the web browser to enforce the Same Origin Policy (SOP) in a more restrictive manner.

### Reference


* [ https://vulncat.fortify.com/en/detail?category=HTML5&subcategory=Overly%20Permissive%20CORS%20Policy ](https://vulncat.fortify.com/en/detail?category=HTML5&subcategory=Overly%20Permissive%20CORS%20Policy)


#### CWE Id: [ 264 ](https://cwe.mitre.org/data/definitions/264.html)


#### WASC Id: 14

#### Source ID: 3

### [ Missing Anti-clickjacking Header ](https://www.zaproxy.org/docs/alerts/10020/)



##### Medium (Medium)

### Description

The response does not protect against 'ClickJacking' attacks. It should include either Content-Security-Policy with 'frame-ancestors' directive or X-Frame-Options.

* URL: https://tfctest-003-production.up.railway.app/
  * Node Name: `https://tfctest-003-production.up.railway.app/`
  * Method: `GET`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/admin
  * Node Name: `https://tfctest-003-production.up.railway.app/admin`
  * Method: `GET`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``


Instances: 2

### Solution

Modern Web browsers support the Content-Security-Policy and X-Frame-Options HTTP headers. Ensure one of them is set on all web pages returned by your site/app.
If you expect the page to be framed only by pages on your server (e.g. it's part of a FRAMESET) then you'll want to use SAMEORIGIN, otherwise if you never expect the page to be framed, you should use DENY. Alternatively consider implementing Content Security Policy's "frame-ancestors" directive.

### Reference


* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/X-Frame-Options ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/X-Frame-Options)


#### CWE Id: [ 1021 ](https://cwe.mitre.org/data/definitions/1021.html)


#### WASC Id: 15

#### Source ID: 3

### [ Big Redirect Detected (Potential Sensitive Information Leak) ](https://www.zaproxy.org/docs/alerts/10044/)



##### Low (Medium)

### Description

The server has responded with a redirect that seems to provide a large response. This may indicate that although the server sent a redirect it also responded with body content (which may include sensitive details, PII, etc.).

* URL: https://tfctest-003-production.up.railway.app/checkout
  * Node Name: `https://tfctest-003-production.up.railway.app/checkout`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: `Location header URI length: 1 [/].
Predicted response size: 301.
Response Body Length: 6,638.`


Instances: 1

### Solution

Ensure that no sensitive information is leaked via redirect responses. Redirect responses should have almost no content.

### Reference



#### CWE Id: [ 201 ](https://cwe.mitre.org/data/definitions/201.html)


#### WASC Id: 13

#### Source ID: 3

### [ Cookie with SameSite Attribute None ](https://www.zaproxy.org/docs/alerts/10054/)



##### Low (Medium)

### Description

A cookie has been set with its SameSite attribute set to "none", which means that the cookie can be sent as a result of a 'cross-site' request. The SameSite attribute is an effective counter measure to cross-site request forgery, cross-site script inclusion, and timing attacks.

* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)`
  * Method: `OPTIONS`
  * Parameter: `__cf_bm`
  * Attack: ``
  * Evidence: `set-cookie: __cf_bm`
  * Other Info: ``
* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)({email,password,gotrue_meta_security:{}})`
  * Method: `POST`
  * Parameter: `__cf_bm`
  * Attack: ``
  * Evidence: `set-cookie: __cf_bm`
  * Other Info: ``


Instances: 2

### Solution

Ensure that the SameSite attribute is set to either 'lax' or ideally 'strict' for all cookies.

### Reference


* [ https://datatracker.ietf.org/doc/html/draft-ietf-httpbis-cookie-same-site ](https://datatracker.ietf.org/doc/html/draft-ietf-httpbis-cookie-same-site)


#### CWE Id: [ 1275 ](https://cwe.mitre.org/data/definitions/1275.html)


#### WASC Id: 13

#### Source ID: 3

### [ Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s) ](https://www.zaproxy.org/docs/alerts/10037/)



##### Low (Medium)

### Description

The web/application server is leaking information via one or more "X-Powered-By" HTTP response headers. Access to such information may facilitate attackers identifying other frameworks/components your web application is reliant upon and the vulnerabilities such components may be subject to.

* URL: https://tfctest-003-production.up.railway.app/
  * Node Name: `https://tfctest-003-production.up.railway.app/`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `x-powered-by: Next.js`
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/admin
  * Node Name: `https://tfctest-003-production.up.railway.app/admin`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `x-powered-by: Next.js`
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/checkout
  * Node Name: `https://tfctest-003-production.up.railway.app/checkout`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `x-powered-by: Next.js`
  * Other Info: ``


Instances: 3

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to suppress "X-Powered-By" headers.

### Reference


* [ https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/08-Fingerprint_Web_Application_Framework ](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/08-Fingerprint_Web_Application_Framework)
* [ https://www.troyhunt.com/shhh-dont-let-your-response-headers/ ](https://www.troyhunt.com/shhh-dont-let-your-response-headers/)


#### CWE Id: [ 497 ](https://cwe.mitre.org/data/definitions/497.html)


#### WASC Id: 13

#### Source ID: 3

### [ Server Leaks Version Information via "Server" HTTP Response Header Field ](https://www.zaproxy.org/docs/alerts/10036/)



##### Low (High)

### Description

The web/application server is leaking version information via the "Server" HTTP response header. Access to such information may facilitate attackers identifying other vulnerabilities your web/application server is subject to.

* URL: https://clientservices.googleapis.com/uma/v2
  * Node Name: `https://clientservices.googleapis.com/uma/v2 ()(2	ÄÝtß­ã®NDQ2	âFy¶8ò...,B 2	É_ª¾ÅzA  ...,	ït Ê<«E ¯õâÔ152.0.7977.82-64...,	3¦VÍ¾}Îü«Ó
ïÞÈÆÞÿ
ú÷¿ð2,	5 Úbmö°!Áùî	Üö2g...,	Nj-tð°Æ  " 2...,	Sß)úáyºµò):ïo2...,	¶$ÃlÑO6¾È´
ïÞÈÆÞÿ
ú÷¿ð2I...,	Ï#µa*Ù)3@P 2$...,	îÉyy¨ D   82a...,þ2	>Z³f)}2	qÅ¥T@ PÂ...,ù.2	A9ÍHýH2	µ ¯#ÃWF..., 2	Vcé¶âÄ/ 2	õ>Çªrª...,*2	F¨¦Ðµ*Ð
 2$	R¾`þûû¥ ...,*2	µÑLoµqØ ùí# 2	¾ï,_B2<	èPEª%ªã©...,1 ¡?ÉQ i
Òô® Åá ...,7     
...,-m«~½ãÁ2	àOãóuò´°...,12	@ô'¡^5,12	bÎ±Wgõ¥Ê2	ëêÈ0*...,-	}ÿÿÿÿ2	ÏmjG^rÞ ,2~	ÚÁå...,ÜËøÖ Ò%3ÓE2)	ÄÊ,ñ.í8øDÌS®eôzÛ
×Â...,ñ.Û×2\	¼Ø§MÓe¿,  ...,Â 2	2Þ¦\G52	<ýîðÍÐ...,`Y 2	¾y1¸2;	7Ás*·%µ~...,Ë
ñw"   2	KÖµ%/...,Ä©á 2	»NøÜ©õ2	SRÝøw...,2	ÛØU¼ã*fp2	½,ÐÊløk2	9¬×...,	2	?ÁÂ¡ßÆ*¨2...,2f	3Jí¶º)¾  A  ...,Ò¤³µ¢2	XjFÊ|a...,-¥4É<F£Q ^m¬...,­18þ?ûR¼^
¼è °..., j w ¤   	...,     	2	..., G < ,   ! (...,L 4_ +w . )º -é ...,V 8q 0 8Ä . Ô ..., 2	Õø!ÄÜ7 2	(Xû DP`¯ ..., 2	äÉD °£ 2/	r§5±B ..., 
2	6ÔEâ²0¼¶\Û, ,   	 2..., @
 @9D @2	tÙ°};z}jT...,3 , Â2	Æ¬¯8W  "29	c°Ü(*×...,' °(º(Á(¥) á* õ...,' °(º(Á(¥) á* õ..., 2	8ÜÿVBÄ¾ 2	çÅT[Ôú7...,1À>2	K¯Aíë2	#þn-÷5...,¨¿·!,øDÌS®eôz
×Â Ðÿÿÿÿ...,'; 2	 XCUh4x 2	ß,$ª...,/	 2	kh½Oµ4 62X	ø1;©Z...,I2	3jcO l2	¦ûwï«q2	¥..., '(* -./0 2..., «)2	©´(ÈXx 2	å[ÿM ·3¸..., - ¥4 É< F £Q ..., ¡æ¯* Ðà/ 	ïÈ0 ÚÃÜ2..., ñ.í8øDÌS®eôz
×Â ..., - ¥4 É< F £Q ..., 46 `ËL ÉlôÚ¥µ..., û2	|Ü9ýà. û2B	Ñ[ÕoëËen¶ ...,#Z2	ý¶Yz,)Ò¾2	Úªæ}^Eµ(2	Óh...,2	Gy7
2	»µ{ãÄº'2	Aí...,2	,2	Ë$ú¥]v@ú 2	¿i¾ûøç¸ 2...,2	éäÍàu  2	W8ÉMïg	 2...,2'	CAâÚÎá,  ...,26	oÕdî $ ...,7E³»   »2	iÙWó@» ...,;,>åk 2.	Ì
÷ä¨bÅ«k 
...,@çí×P8	 	2	×'/%Ñ"0P 2	­`£#...,B¦ÜËøÖ Ò%3ÓE2;	...,Fj.a 2	ùDÊ)]H2-	...,KÇ«k<2	,P¹m|	,VÉp#¹î 2	¡+åHi82	Jà¿...,Wc33Ðñc2	%¦*Ær   2	 ...,Wë;µ2	weQ½ î2	ßLéöS5...,Y2	Ð$¦DâÏß2	zË²ÿ×ÍeÍ¬ø
...,báËD2	íµ;t]÷f\2	zÏ\®%U...,cuìÚÂè2	LdY/ª´j¤ÚÂè2	...,cðG·B2	ìÅ	û¢{2	;¸Mú©Ôº×±...,eJø¨ 2	54{ dQ 	2	7qAoÑª...,fe<  2	×ðY,hÃ¾2	Ø*§Ìÿ 2	ÁD¬...,r%¾Dj 2	úå"ïà 2	ØAÔÓ¡+...,sTLÎ   2	zþ\ÿR  2	ÿÅÕUn·...,tØÖÒ®2	%ËÝö62	ÇCC*´	J...,w¾2	fàü© 12	~nÕ°2F...,w¾{x	2!	U"5¯Å:-   ...,x§Q ÈÉ2	}ýªóÈÉ2	°71ôò...,yüR¨oæÞJ
6¼¨oæÞJ
q¤¨oæÞJ
Ü¿qÿ...,{õ²¾`¼2	3|ôÖd»À2	8Ós2Ë...,| 2	Vð¹ï 2	yY@w_Õ...,~5 2	¶r'}_ð 2	ÐõÀàb$...,~¨mt2	,¹5xÊu¢ë2	%§Ä2...,¥­¯Ëº 2	áÛ2		mLc<...,¬¢ûû2	Ä#wâî2	{©6Þ zØ...,K8ò2	ý÷ó¶~û2	­GkbH8...,bRß 	38<CL N...,mÆð     ...,ó@Ë_1    
...,89b©ì± AVqÄ ..., ÌD2	½K·pÿ§2	\ÒLþ2	..., Öª2	¦¿uÍàs2	QpL±K_...,£qË{|å2	3d­Õ£z:2	`GPhºÀ0...,¤ïº2	¿Ã?Ôì½æKìCÿ½X2	n'Mu'...,¨§42	v	_]§"?2	¹§¼-Íß2...,ª¶×¸I"2	q8~A)Rïþ2	sµõQÏ6«...,«2	Þ35EkÂ2	,«HîH0@  2'	bÒÓåìoþ' ...,®¨ìþh	 2	zz	£ò.<Ûd§...,¯2	5	¶W>«® 2	Ô»elÇTk 2...,¯;ô2	^jøÐ×332	Cöôõ6Æ`2...,°!lñéòé2	.Oêâ)¦dèÌé...,´vX, 2ê	RMºDgà Ü	...,µ¶ËiÑÁ2	ûÖ«L±3¿¥Ê...,ºC2	¯áòÉð02	v_,Ñ W...,»F÷}é¤î2 6  	  ...,¿ÍÛÿ Ã
 î   ...,ÅÍ¢müE!)@ Pd2<	åÍ)...,Æ2	0Å[^Y{û2	][w°#fV...,ÊÎ 4BTk¾Ù	...,Î³   2	ýê5öÐp ...,Îð:¸´ÔPÒrÉ
ëÓù 2	Z...,Ï´X.#ÚØÄ  Ô À ...,Ð~ ´h2	åð'(çØé­   2	Ù...,Ñ¨¼2	}¸>1¸2	÷](.2	...,Ñ÷pÔ 2	2"Lü~ý ...,Ô}/`-wLiË2	w_¯îÓgv...,Ô¿2	Û]g«_cf2	¡­Ì}Kk2...,çBÏ 2	8(à,éy[,îIÄäÎäï    ...,î¡v  2	Ù¼­A£÷A6E 
 !...,ïÎzñó2	 í3 á2	D²ö...,ñ/2	.ÞÒ#¾¡2	bPÈ8Æ52	È...,ñ³*ø¹: 
 2	pIÈüýÁ2...,õ,2	ò2^¶R2	¾;êÅïÝÈ...,÷R§ß÷® BTk ¾...,úwªjÕ  	  ...,ýYGxÖË¢2	y/ó%2TUÇ ­ ...,ÿTeüÜrµ2	æàòQÈÉëõÇ10¯92...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: `scaffolding on HTTPServer2`
  * Other Info: ``


Instances: 1

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to suppress the "Server" header or provide generic details.

### Reference


* [ https://httpd.apache.org/docs/current/mod/core.html#servertokens ](https://httpd.apache.org/docs/current/mod/core.html#servertokens)
* [ https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff648552(v=pandp.10) ](https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff648552(v=pandp.10))
* [ https://www.troyhunt.com/shhh-dont-let-your-response-headers/ ](https://www.troyhunt.com/shhh-dont-let-your-response-headers/)


#### CWE Id: [ 497 ](https://cwe.mitre.org/data/definitions/497.html)


#### WASC Id: 13

#### Source ID: 3

### [ Strict-Transport-Security Header Not Set ](https://www.zaproxy.org/docs/alerts/10035/)



##### Low (High)

### Description

HTTP Strict Transport Security (HSTS) is a web security policy mechanism whereby a web server declares that complying user agents (such as a web browser) are to interact with it using only secure HTTPS connections (i.e. HTTP layered over TLS/SSL). HSTS is an IETF standards track protocol and is specified in RFC 6797.

* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCZlNxi0Kdn2oEg8Ng6hbPSoIEAUYBSAESAUSDw3OQUx6KggQAhgCIARIAiGY6Q9D31LNUCn0b1HFpJW5xjICIAI=%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCZlNxi0Kdn2oEg8Ng6hbPSoIEAUYBSAESAUSDw3OQUx6KggQAhgCIARIAiGY6Q9D31LNUCn0b1HFpJW5xjICIAI= (alt)`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJjCS6Ur2YWwWxqEg8NlFT6zyoIEAMYASADOAMSDw09LLzYKggQBhgHIAI4AhIPDQbWhTIqCBABGAIgADgAEg8NbCez7CoIEAMYBCABOAEhnIfrb6qZT88pnIfrb6qZT88yAiAF%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJjCS6Ur2YWwWxqEg8NlFT6zyoIEAMYASADOAMSDw09LLzYKggQBhgHIAI4AhIPDQbWhTIqCBABGAIgADgAEg8NbCez7CoIEAMYBCABOAEhnIfrb6qZT88pnIfrb6qZT88yAiAF (alt)`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/
  * Node Name: `https://tfctest-003-production.up.railway.app/`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/2-asbtym1dph6.css
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/2-asbtym1dph6.css`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/2mmpezlrfmbu5.js
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/2mmpezlrfmbu5.js`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/310vm2bl3xxpt.js
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/310vm2bl3xxpt.js`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/turbopack-3f9dlf6wkixxm.js
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/turbopack-3f9dlf6wkixxm.js`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://clientservices.googleapis.com/uma/v2
  * Node Name: `https://clientservices.googleapis.com/uma/v2 ()(2	ÄÝtß­ã®NDQ2	âFy¶8ò...,B 2	É_ª¾ÅzA  ...,	ït Ê<«E ¯õâÔ152.0.7977.82-64...,	3¦VÍ¾}Îü«Ó
ïÞÈÆÞÿ
ú÷¿ð2,	5 Úbmö°!Áùî	Üö2g...,	Nj-tð°Æ  " 2...,	Sß)úáyºµò):ïo2...,	¶$ÃlÑO6¾È´
ïÞÈÆÞÿ
ú÷¿ð2I...,	Ï#µa*Ù)3@P 2$...,	îÉyy¨ D   82a...,þ2	>Z³f)}2	qÅ¥T@ PÂ...,ù.2	A9ÍHýH2	µ ¯#ÃWF..., 2	Vcé¶âÄ/ 2	õ>Çªrª...,*2	F¨¦Ðµ*Ð
 2$	R¾`þûû¥ ...,*2	µÑLoµqØ ùí# 2	¾ï,_B2<	èPEª%ªã©...,1 ¡?ÉQ i
Òô® Åá ...,7     
...,-m«~½ãÁ2	àOãóuò´°...,12	@ô'¡^5,12	bÎ±Wgõ¥Ê2	ëêÈ0*...,-	}ÿÿÿÿ2	ÏmjG^rÞ ,2~	ÚÁå...,ÜËøÖ Ò%3ÓE2)	ÄÊ,ñ.í8øDÌS®eôzÛ
×Â...,ñ.Û×2\	¼Ø§MÓe¿,  ...,Â 2	2Þ¦\G52	<ýîðÍÐ...,`Y 2	¾y1¸2;	7Ás*·%µ~...,Ë
ñw"   2	KÖµ%/...,Ä©á 2	»NøÜ©õ2	SRÝøw...,2	ÛØU¼ã*fp2	½,ÐÊløk2	9¬×...,	2	?ÁÂ¡ßÆ*¨2...,2f	3Jí¶º)¾  A  ...,Ò¤³µ¢2	XjFÊ|a...,-¥4É<F£Q ^m¬...,­18þ?ûR¼^
¼è °..., j w ¤   	...,     	2	..., G < ,   ! (...,L 4_ +w . )º -é ...,V 8q 0 8Ä . Ô ..., 2	Õø!ÄÜ7 2	(Xû DP`¯ ..., 2	äÉD °£ 2/	r§5±B ..., 
2	6ÔEâ²0¼¶\Û, ,   	 2..., @
 @9D @2	tÙ°};z}jT...,3 , Â2	Æ¬¯8W  "29	c°Ü(*×...,' °(º(Á(¥) á* õ...,' °(º(Á(¥) á* õ..., 2	8ÜÿVBÄ¾ 2	çÅT[Ôú7...,1À>2	K¯Aíë2	#þn-÷5...,¨¿·!,øDÌS®eôz
×Â Ðÿÿÿÿ...,'; 2	 XCUh4x 2	ß,$ª...,/	 2	kh½Oµ4 62X	ø1;©Z...,I2	3jcO l2	¦ûwï«q2	¥..., '(* -./0 2..., «)2	©´(ÈXx 2	å[ÿM ·3¸..., - ¥4 É< F £Q ..., ¡æ¯* Ðà/ 	ïÈ0 ÚÃÜ2..., ñ.í8øDÌS®eôz
×Â ..., - ¥4 É< F £Q ..., 46 `ËL ÉlôÚ¥µ..., û2	|Ü9ýà. û2B	Ñ[ÕoëËen¶ ...,#Z2	ý¶Yz,)Ò¾2	Úªæ}^Eµ(2	Óh...,2	Gy7
2	»µ{ãÄº'2	Aí...,2	,2	Ë$ú¥]v@ú 2	¿i¾ûøç¸ 2...,2	éäÍàu  2	W8ÉMïg	 2...,2'	CAâÚÎá,  ...,26	oÕdî $ ...,7E³»   »2	iÙWó@» ...,;,>åk 2.	Ì
÷ä¨bÅ«k 
...,@çí×P8	 	2	×'/%Ñ"0P 2	­`£#...,B¦ÜËøÖ Ò%3ÓE2;	...,Fj.a 2	ùDÊ)]H2-	...,KÇ«k<2	,P¹m|	,VÉp#¹î 2	¡+åHi82	Jà¿...,Wc33Ðñc2	%¦*Ær   2	 ...,Wë;µ2	weQ½ î2	ßLéöS5...,Y2	Ð$¦DâÏß2	zË²ÿ×ÍeÍ¬ø
...,báËD2	íµ;t]÷f\2	zÏ\®%U...,cuìÚÂè2	LdY/ª´j¤ÚÂè2	...,cðG·B2	ìÅ	û¢{2	;¸Mú©Ôº×±...,eJø¨ 2	54{ dQ 	2	7qAoÑª...,fe<  2	×ðY,hÃ¾2	Ø*§Ìÿ 2	ÁD¬...,r%¾Dj 2	úå"ïà 2	ØAÔÓ¡+...,sTLÎ   2	zþ\ÿR  2	ÿÅÕUn·...,tØÖÒ®2	%ËÝö62	ÇCC*´	J...,w¾2	fàü© 12	~nÕ°2F...,w¾{x	2!	U"5¯Å:-   ...,x§Q ÈÉ2	}ýªóÈÉ2	°71ôò...,yüR¨oæÞJ
6¼¨oæÞJ
q¤¨oæÞJ
Ü¿qÿ...,{õ²¾`¼2	3|ôÖd»À2	8Ós2Ë...,| 2	Vð¹ï 2	yY@w_Õ...,~5 2	¶r'}_ð 2	ÐõÀàb$...,~¨mt2	,¹5xÊu¢ë2	%§Ä2...,¥­¯Ëº 2	áÛ2		mLc<...,¬¢ûû2	Ä#wâî2	{©6Þ zØ...,K8ò2	ý÷ó¶~û2	­GkbH8...,bRß 	38<CL N...,mÆð     ...,ó@Ë_1    
...,89b©ì± AVqÄ ..., ÌD2	½K·pÿ§2	\ÒLþ2	..., Öª2	¦¿uÍàs2	QpL±K_...,£qË{|å2	3d­Õ£z:2	`GPhºÀ0...,¤ïº2	¿Ã?Ôì½æKìCÿ½X2	n'Mu'...,¨§42	v	_]§"?2	¹§¼-Íß2...,ª¶×¸I"2	q8~A)Rïþ2	sµõQÏ6«...,«2	Þ35EkÂ2	,«HîH0@  2'	bÒÓåìoþ' ...,®¨ìþh	 2	zz	£ò.<Ûd§...,¯2	5	¶W>«® 2	Ô»elÇTk 2...,¯;ô2	^jøÐ×332	Cöôõ6Æ`2...,°!lñéòé2	.Oêâ)¦dèÌé...,´vX, 2ê	RMºDgà Ü	...,µ¶ËiÑÁ2	ûÖ«L±3¿¥Ê...,ºC2	¯áòÉð02	v_,Ñ W...,»F÷}é¤î2 6  	  ...,¿ÍÛÿ Ã
 î   ...,ÅÍ¢müE!)@ Pd2<	åÍ)...,Æ2	0Å[^Y{û2	][w°#fV...,ÊÎ 4BTk¾Ù	...,Î³   2	ýê5öÐp ...,Îð:¸´ÔPÒrÉ
ëÓù 2	Z...,Ï´X.#ÚØÄ  Ô À ...,Ð~ ´h2	åð'(çØé­   2	Ù...,Ñ¨¼2	}¸>1¸2	÷](.2	...,Ñ÷pÔ 2	2"Lü~ý ...,Ô}/`-wLiË2	w_¯îÓgv...,Ô¿2	Û]g«_cf2	¡­Ì}Kk2...,çBÏ 2	8(à,éy[,îIÄäÎäï    ...,î¡v  2	Ù¼­A£÷A6E 
 !...,ïÎzñó2	 í3 á2	D²ö...,ñ/2	.ÞÒ#¾¡2	bPÈ8Æ52	È...,ñ³*ø¹: 
 2	pIÈüýÁ2...,õ,2	ò2^¶R2	¾;êÅïÝÈ...,÷R§ß÷® BTk ¾...,úwªjÕ  	  ...,ýYGxÖË¢2	y/ó%2TUÇ ­ ...,ÿTeüÜrµ2	æàòQÈÉëõÇ10¯92...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/forms:vote%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/forms:vote (alt)(
ç
Chrome/152.0.7977.82.¯fÁlj " x...,Êªø\!nöÜ©Q:$ ó"¬nøïí§Ëy¡ ¥bÔa...,Jó$ ÒÊ~0(¡ÇÿÉ¯4dø»ùâÝú÷÷éfM_¢b...,~)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json
  * Node Name: `https://update.googleapis.com/service/update2/json ()({request:{@os,@updater,acceptformat,apps:[{accept_locale,appid,cohort,cohortname,enabled,events:[{download_time_ms,downloaded,downloader,eventresult,eventtype,nextversion,pipeline_id,previousversion,total,url},{eventresult,eventtype,nextversion,pipeline_id,previousversion}..,{eventresult,eventtype,nextversion,previousversion}],installdate,lang,version}],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodversion,protocol,requestid,sessionid...)`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json%3Fcup2key=16:JwNE4QFEk-TTdbwK3og-HDtSVrbD82t7L6GkjenoH5Q&cup2hreq=a2d1d2dcd6d8b177d223966a3c4ef334887fe1d1ebd890c7a5d53acaf75df6ea
  * Node Name: `https://update.googleapis.com/service/update2/json (cup2hreq,cup2key)({request:{@os,@updater,acceptformat,apps:[{appid,enabled,installdate,ping:{ad,r},release_channel,updatecheck:{updatedisabled},version}],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodchannel,prodversion,protocol,requestid,sessionid,updaterchannel,updaterversion}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: https://update.googleapis.com/service/update2/json%3Fcup2key=16:q9XNu8u0IExsoq99Y9lmRb8_8a6hGIrOo4zMKu95K-c&cup2hreq=a6de6323207e3588ae6e5b21248bc0385b2a46f066547798854e77fc5977a3d9
  * Node Name: `https://update.googleapis.com/service/update2/json (cup2hreq,cup2key)({request:{@os,@updater,acceptformat,apps:[{appid,enabled,lang,ping:{r},updatecheck:{},version}..,{accept_locale,appid,enabled,lang,ping:{r},updatecheck:{},version},{appid,enabled,lang,ping:{r},updatecheck:{},version}..],arch,dedup,domainjoined,hw:{avx,physmemory,sse,sse2,sse3,sse41,sse42,ssse3},ismachine,os:{arch,platform,version},prodversion,protocol,requestid,sessionid,updaters:{autoupdatecheckenabled,ismachine,lastchecked,laststarted,name,updatepolicy,version},updaterversion}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``

Instances: Systemic


### Solution

Ensure that your web server, application server, load balancer, etc. is configured to enforce Strict-Transport-Security.

### Reference


* [ https://cheatsheetseries.owasp.org/cheatsheets/HTTP_Strict_Transport_Security_Cheat_Sheet.html ](https://cheatsheetseries.owasp.org/cheatsheets/HTTP_Strict_Transport_Security_Cheat_Sheet.html)
* [ https://owasp.org/www-community/Security_Headers ](https://owasp.org/www-community/Security_Headers)
* [ https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security ](https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security)
* [ https://caniuse.com/stricttransportsecurity ](https://caniuse.com/stricttransportsecurity)
* [ https://datatracker.ietf.org/doc/html/rfc6797 ](https://datatracker.ietf.org/doc/html/rfc6797)


#### CWE Id: [ 319 ](https://cwe.mitre.org/data/definitions/319.html)


#### WASC Id: 15

#### Source ID: 3

### [ Timestamp Disclosure - Unix ](https://www.zaproxy.org/docs/alerts/10096/)



##### Low (Low)

### Description

A timestamp was disclosed by the application/web server. - Unix

* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)`
  * Method: `OPTIONS`
  * Parameter: `set-cookie`
  * Attack: ``
  * Evidence: `1788778038`
  * Other Info: `1788778038, which evaluates to: 2026-09-07 16:47:18.`
* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)({email,password,gotrue_meta_security:{}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: `1788781638`
  * Other Info: `1788781638, which evaluates to: 2026-09-07 17:47:18.`
* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)({email,password,gotrue_meta_security:{}})`
  * Method: `POST`
  * Parameter: `set-cookie`
  * Attack: ``
  * Evidence: `1788778038`
  * Other Info: `1788778038, which evaluates to: 2026-09-07 16:47:18.`


Instances: 3

### Solution

Manually confirm that the timestamp data is not sensitive, and that the data cannot be aggregated to disclose exploitable patterns.

### Reference


* [ https://cwe.mitre.org/data/definitions/200.html ](https://cwe.mitre.org/data/definitions/200.html)


#### CWE Id: [ 497 ](https://cwe.mitre.org/data/definitions/497.html)


#### WASC Id: 13

#### Source ID: 3

### [ X-Content-Type-Options Header Missing ](https://www.zaproxy.org/docs/alerts/10021/)



##### Low (Medium)

### Description

The Anti-MIME-Sniffing header X-Content-Type-Options was not set to 'nosniff'. This allows older versions of Internet Explorer and Chrome to perform MIME-sniffing on the response body, potentially causing the response body to be interpreted and displayed as a content type other than the declared content type. Current (early 2014) and legacy versions of Firefox will use the declared content type (if one is set), rather than performing MIME-sniffing.

* URL: https://tfctest-003-production.up.railway.app/
  * Node Name: `https://tfctest-003-production.up.railway.app/`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/2-asbtym1dph6.css
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/2-asbtym1dph6.css`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/2mmpezlrfmbu5.js
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/2mmpezlrfmbu5.js`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/310vm2bl3xxpt.js
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/310vm2bl3xxpt.js`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://tfctest-003-production.up.railway.app/_next/static/chunks/turbopack-3f9dlf6wkixxm.js
  * Node Name: `https://tfctest-003-production.up.railway.app/_next/static/chunks/turbopack-3f9dlf6wkixxm.js`
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: https://clientservices.googleapis.com/uma/v2
  * Node Name: `https://clientservices.googleapis.com/uma/v2 ()(2	ÄÝtß­ã®NDQ2	âFy¶8ò...,B 2	É_ª¾ÅzA  ...,	ït Ê<«E ¯õâÔ152.0.7977.82-64...,	3¦VÍ¾}Îü«Ó
ïÞÈÆÞÿ
ú÷¿ð2,	5 Úbmö°!Áùî	Üö2g...,	Nj-tð°Æ  " 2...,	Sß)úáyºµò):ïo2...,	¶$ÃlÑO6¾È´
ïÞÈÆÞÿ
ú÷¿ð2I...,	Ï#µa*Ù)3@P 2$...,	îÉyy¨ D   82a...,þ2	>Z³f)}2	qÅ¥T@ PÂ...,ù.2	A9ÍHýH2	µ ¯#ÃWF..., 2	Vcé¶âÄ/ 2	õ>Çªrª...,*2	F¨¦Ðµ*Ð
 2$	R¾`þûû¥ ...,*2	µÑLoµqØ ùí# 2	¾ï,_B2<	èPEª%ªã©...,1 ¡?ÉQ i
Òô® Åá ...,7     
...,-m«~½ãÁ2	àOãóuò´°...,12	@ô'¡^5,12	bÎ±Wgõ¥Ê2	ëêÈ0*...,-	}ÿÿÿÿ2	ÏmjG^rÞ ,2~	ÚÁå...,ÜËøÖ Ò%3ÓE2)	ÄÊ,ñ.í8øDÌS®eôzÛ
×Â...,ñ.Û×2\	¼Ø§MÓe¿,  ...,Â 2	2Þ¦\G52	<ýîðÍÐ...,`Y 2	¾y1¸2;	7Ás*·%µ~...,Ë
ñw"   2	KÖµ%/...,Ä©á 2	»NøÜ©õ2	SRÝøw...,2	ÛØU¼ã*fp2	½,ÐÊløk2	9¬×...,	2	?ÁÂ¡ßÆ*¨2...,2f	3Jí¶º)¾  A  ...,Ò¤³µ¢2	XjFÊ|a...,-¥4É<F£Q ^m¬...,­18þ?ûR¼^
¼è °..., j w ¤   	...,     	2	..., G < ,   ! (...,L 4_ +w . )º -é ...,V 8q 0 8Ä . Ô ..., 2	Õø!ÄÜ7 2	(Xû DP`¯ ..., 2	äÉD °£ 2/	r§5±B ..., 
2	6ÔEâ²0¼¶\Û, ,   	 2..., @
 @9D @2	tÙ°};z}jT...,3 , Â2	Æ¬¯8W  "29	c°Ü(*×...,' °(º(Á(¥) á* õ...,' °(º(Á(¥) á* õ..., 2	8ÜÿVBÄ¾ 2	çÅT[Ôú7...,1À>2	K¯Aíë2	#þn-÷5...,¨¿·!,øDÌS®eôz
×Â Ðÿÿÿÿ...,'; 2	 XCUh4x 2	ß,$ª...,/	 2	kh½Oµ4 62X	ø1;©Z...,I2	3jcO l2	¦ûwï«q2	¥..., '(* -./0 2..., «)2	©´(ÈXx 2	å[ÿM ·3¸..., - ¥4 É< F £Q ..., ¡æ¯* Ðà/ 	ïÈ0 ÚÃÜ2..., ñ.í8øDÌS®eôz
×Â ..., - ¥4 É< F £Q ..., 46 `ËL ÉlôÚ¥µ..., û2	|Ü9ýà. û2B	Ñ[ÕoëËen¶ ...,#Z2	ý¶Yz,)Ò¾2	Úªæ}^Eµ(2	Óh...,2	Gy7
2	»µ{ãÄº'2	Aí...,2	,2	Ë$ú¥]v@ú 2	¿i¾ûøç¸ 2...,2	éäÍàu  2	W8ÉMïg	 2...,2'	CAâÚÎá,  ...,26	oÕdî $ ...,7E³»   »2	iÙWó@» ...,;,>åk 2.	Ì
÷ä¨bÅ«k 
...,@çí×P8	 	2	×'/%Ñ"0P 2	­`£#...,B¦ÜËøÖ Ò%3ÓE2;	...,Fj.a 2	ùDÊ)]H2-	...,KÇ«k<2	,P¹m|	,VÉp#¹î 2	¡+åHi82	Jà¿...,Wc33Ðñc2	%¦*Ær   2	 ...,Wë;µ2	weQ½ î2	ßLéöS5...,Y2	Ð$¦DâÏß2	zË²ÿ×ÍeÍ¬ø
...,báËD2	íµ;t]÷f\2	zÏ\®%U...,cuìÚÂè2	LdY/ª´j¤ÚÂè2	...,cðG·B2	ìÅ	û¢{2	;¸Mú©Ôº×±...,eJø¨ 2	54{ dQ 	2	7qAoÑª...,fe<  2	×ðY,hÃ¾2	Ø*§Ìÿ 2	ÁD¬...,r%¾Dj 2	úå"ïà 2	ØAÔÓ¡+...,sTLÎ   2	zþ\ÿR  2	ÿÅÕUn·...,tØÖÒ®2	%ËÝö62	ÇCC*´	J...,w¾2	fàü© 12	~nÕ°2F...,w¾{x	2!	U"5¯Å:-   ...,x§Q ÈÉ2	}ýªóÈÉ2	°71ôò...,yüR¨oæÞJ
6¼¨oæÞJ
q¤¨oæÞJ
Ü¿qÿ...,{õ²¾`¼2	3|ôÖd»À2	8Ós2Ë...,| 2	Vð¹ï 2	yY@w_Õ...,~5 2	¶r'}_ð 2	ÐõÀàb$...,~¨mt2	,¹5xÊu¢ë2	%§Ä2...,¥­¯Ëº 2	áÛ2		mLc<...,¬¢ûû2	Ä#wâî2	{©6Þ zØ...,K8ò2	ý÷ó¶~û2	­GkbH8...,bRß 	38<CL N...,mÆð     ...,ó@Ë_1    
...,89b©ì± AVqÄ ..., ÌD2	½K·pÿ§2	\ÒLþ2	..., Öª2	¦¿uÍàs2	QpL±K_...,£qË{|å2	3d­Õ£z:2	`GPhºÀ0...,¤ïº2	¿Ã?Ôì½æKìCÿ½X2	n'Mu'...,¨§42	v	_]§"?2	¹§¼-Íß2...,ª¶×¸I"2	q8~A)Rïþ2	sµõQÏ6«...,«2	Þ35EkÂ2	,«HîH0@  2'	bÒÓåìoþ' ...,®¨ìþh	 2	zz	£ò.<Ûd§...,¯2	5	¶W>«® 2	Ô»elÇTk 2...,¯;ô2	^jøÐ×332	Cöôõ6Æ`2...,°!lñéòé2	.Oêâ)¦dèÌé...,´vX, 2ê	RMºDgà Ü	...,µ¶ËiÑÁ2	ûÖ«L±3¿¥Ê...,ºC2	¯áòÉð02	v_,Ñ W...,»F÷}é¤î2 6  	  ...,¿ÍÛÿ Ã
 î   ...,ÅÍ¢müE!)@ Pd2<	åÍ)...,Æ2	0Å[^Y{û2	][w°#fV...,ÊÎ 4BTk¾Ù	...,Î³   2	ýê5öÐp ...,Îð:¸´ÔPÒrÉ
ëÓù 2	Z...,Ï´X.#ÚØÄ  Ô À ...,Ð~ ´h2	åð'(çØé­   2	Ù...,Ñ¨¼2	}¸>1¸2	÷](.2	...,Ñ÷pÔ 2	2"Lü~ý ...,Ô}/`-wLiË2	w_¯îÓgv...,Ô¿2	Û]g«_cf2	¡­Ì}Kk2...,çBÏ 2	8(à,éy[,îIÄäÎäï    ...,î¡v  2	Ù¼­A£÷A6E 
 !...,ïÎzñó2	 í3 á2	D²ö...,ñ/2	.ÞÒ#¾¡2	bPÈ8Æ52	È...,ñ³*ø¹: 
 2	pIÈüýÁ2...,õ,2	ò2^¶R2	¾;êÅïÝÈ...,÷R§ß÷® BTk ¾...,úwªjÕ  	  ...,ýYGxÖË¢2	y/ó%2TUÇ ­ ...,ÿTeüÜrµ2	æàòQÈÉëõÇ10¯92...)`
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`

Instances: Systemic


### Solution

Ensure that the application/web server sets the Content-Type header appropriately, and that it sets the X-Content-Type-Options header to 'nosniff' for all web pages.
If possible, ensure that the end user uses a standards-compliant and modern web browser that does not perform MIME-sniffing at all, or that can be directed by the web application/web server to not perform MIME-sniffing.

### Reference


* [ https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85) ](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85))
* [ https://owasp.org/www-community/Security_Headers ](https://owasp.org/www-community/Security_Headers)


#### CWE Id: [ 693 ](https://cwe.mitre.org/data/definitions/693.html)


#### WASC Id: 15

#### Source ID: 3

### [ Authentication Request Identified ](https://www.zaproxy.org/docs/alerts/10111/)



##### Informational (Low)

### Description

The given request has been identified as an authentication request. The 'Other Info' field contains a set of key=value lines which identify any relevant fields. If the request is in a context which has an Authentication Method set to "Auto-Detect" then this rule will change the authentication to match the request identified.

* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)({email,password,gotrue_meta_security:{}})`
  * Method: `POST`
  * Parameter: `email`
  * Attack: ``
  * Evidence: `password`
  * Other Info: `userParam=email
userValue=ideamanager6@gmail.com
passwordParam=password
referer=https://tfctest-003-production.up.railway.app/`


Instances: 1

### Solution

This is an informational alert rather than a vulnerability and so there is nothing to fix.

### Reference


* [ https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/ ](https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/)



#### Source ID: 3

### [ Content-Type Header Missing ](https://www.zaproxy.org/docs/alerts/10019/)



##### Informational (Medium)

### Description

The Content-Type header was either missing or empty.

* URL: https://tfctest-003-production.up.railway.app/checkout%3F_rsc=5CB68i4pnAekjehf
  * Node Name: `https://tfctest-003-production.up.railway.app/checkout (_rsc)`
  * Method: `GET`
  * Parameter: `content-type`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``


Instances: 1

### Solution

Ensure each page is setting the specific and appropriate content-type value for the content being delivered.

### Reference


* [ https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85) ](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85))


#### CWE Id: [ 345 ](https://cwe.mitre.org/data/definitions/345.html)


#### WASC Id: 12

#### Source ID: 3

### [ Loosely Scoped Cookie ](https://www.zaproxy.org/docs/alerts/90033/)



##### Informational (Low)

### Description

Cookies can be scoped by domain or path. This check is only concerned with domain scope.The domain scope applied to a cookie determines which domains can access it. For example, a cookie can be scoped strictly to a subdomain e.g. www.nottrusted.com, or loosely scoped to a parent domain e.g. nottrusted.com. In the latter case, any subdomain of nottrusted.com can access the cookie. Loosely scoped cookies are common in mega-applications like google.com and live.com. Cookies set from a subdomain like app.foo.bar are transmitted only to that domain by the browser. However, cookies scoped to a parent-level domain may be transmitted to the parent, or any subdomain of the parent.

* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)`
  * Method: `OPTIONS`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Domain=supabase.co`
  * Other Info: `The origin domain used for comparison was:
zznkykduwjrefvxoiwkx.supabase.co
Cookie name: __cf_bm
`
* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)({email,password,gotrue_meta_security:{}})`
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Domain=supabase.co`
  * Other Info: `The origin domain used for comparison was:
zznkykduwjrefvxoiwkx.supabase.co
Cookie name: __cf_bm
`


Instances: 2

### Solution

Always scope cookies to a FQDN (Fully Qualified Domain Name).

### Reference


* [ https://datatracker.ietf.org/doc/html/rfc6265#section-4.1 ](https://datatracker.ietf.org/doc/html/rfc6265#section-4.1)
* [ https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/06-Session_Management_Testing/02-Testing_for_Cookies_Attributes.html ](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/06-Session_Management_Testing/02-Testing_for_Cookies_Attributes.html)
* [ https://code.google.com/archive/p/browsersec/wikis/Part2.wiki ](https://code.google.com/archive/p/browsersec/wikis/Part2.wiki)


#### CWE Id: [ 565 ](https://cwe.mitre.org/data/definitions/565.html)


#### WASC Id: 15

#### Source ID: 3

### [ Modern Web Application ](https://www.zaproxy.org/docs/alerts/10109/)



##### Informational (Medium)

### Description

The application appears to be a modern web application. If you need to explore it automatically then the Client Spider may well be more effective than the standard one.

* URL: https://tfctest-003-production.up.railway.app/checkout
  * Node Name: `https://tfctest-003-production.up.railway.app/checkout`
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `<script src="/_next/static/chunks/2mmpezlrfmbu5.js" async=""></script>`
  * Other Info: `No links have been found while there are scripts, which is an indication that this is a modern web application.`


Instances: 1

### Solution

This is an informational alert and so no changes are required.

### Reference




#### Source ID: 3

### [ Re-examine Cache-control Directives ](https://www.zaproxy.org/docs/alerts/10015/)



##### Informational (Low)

### Description

The cache-control header has not been set properly or is missing, allowing the browser and proxies to cache content. For static assets like css, js, or image files this might be intended, however, the resources should be reviewed to ensure that no sensitive content will be cached.

* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCZlNxi0Kdn2oEg8Ng6hbPSoIEAUYBSAESAUSDw3OQUx6KggQAhgCIARIAiGY6Q9D31LNUCn0b1HFpJW5xjICIAI=%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJBCZlNxi0Kdn2oEg8Ng6hbPSoIEAUYBSAESAUSDw3OQUx6KggQAhgCIARIAiGY6Q9D31LNUCn0b1HFpJW5xjICIAI= (alt)`
  * Method: `GET`
  * Parameter: `cache-control`
  * Attack: ``
  * Evidence: `private,max-age=604800`
  * Other Info: ``
* URL: https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJjCS6Ur2YWwWxqEg8NlFT6zyoIEAMYASADOAMSDw09LLzYKggQBhgHIAI4AhIPDQbWhTIqCBABGAIgADgAEg8NbCez7CoIEAMYBCABOAEhnIfrb6qZT88pnIfrb6qZT88yAiAF%3Falt=proto
  * Node Name: `https://content-autofill.googleapis.com/v1/pages/ChRDaHJvbWUvMTUyLjAuNzk3Ny44MhJjCS6Ur2YWwWxqEg8NlFT6zyoIEAMYASADOAMSDw09LLzYKggQBhgHIAI4AhIPDQbWhTIqCBABGAIgADgAEg8NbCez7CoIEAMYBCABOAEhnIfrb6qZT88pnIfrb6qZT88yAiAF (alt)`
  * Method: `GET`
  * Parameter: `cache-control`
  * Attack: ``
  * Evidence: `private,max-age=604800`
  * Other Info: ``


Instances: 2

### Solution

For secure content, ensure the cache-control HTTP header is set with "no-cache, no-store, must-revalidate". If an asset should be cached consider setting the directives "public, max-age, immutable".

### Reference


* [ https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#web-content-caching ](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#web-content-caching)
* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Cache-Control ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Cache-Control)
* [ https://grayduck.mn/2021/09/13/cache-control-recommendations/ ](https://grayduck.mn/2021/09/13/cache-control-recommendations/)


#### CWE Id: [ 525 ](https://cwe.mitre.org/data/definitions/525.html)


#### WASC Id: 13

#### Source ID: 3

### [ Session Management Response Identified ](https://www.zaproxy.org/docs/alerts/10112/)



##### Informational (Medium)

### Description

The given response has been identified as containing a session management token. The 'Other Info' field contains a set of header tokens that can be used in the Header Based Session Management Method. If the request is in a context which has a Session Management Method set to "Auto-Detect" then this rule will change the session management to use the tokens identified.

* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)`
  * Method: `OPTIONS`
  * Parameter: `__cf_bm`
  * Attack: ``
  * Evidence: `__cf_bm`
  * Other Info: `cookie:__cf_bm`
* URL: https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token%3Fgrant_type=password
  * Node Name: `https://zznkykduwjrefvxoiwkx.supabase.co/auth/v1/token (grant_type)({email,password,gotrue_meta_security:{}})`
  * Method: `POST`
  * Parameter: `__cf_bm`
  * Attack: ``
  * Evidence: `__cf_bm`
  * Other Info: `cookie:__cf_bm`


Instances: 2

### Solution

This is an informational alert rather than a vulnerability and so there is nothing to fix.

### Reference


* [ https://www.zaproxy.org/docs/desktop/addons/authentication-helper/session-mgmt-id/ ](https://www.zaproxy.org/docs/desktop/addons/authentication-helper/session-mgmt-id/)



#### Source ID: 3

### [ User Agent Fuzzer ](https://www.zaproxy.org/docs/alerts/10104/)



##### Informational (Medium)

### Description

Check for differences in response based on fuzzed User Agent (eg. mobile sites, access as a Search Engine Crawler). Compares the response statuscode and the hashcode of the response body with the original response.

* URL: https://tfctest-003-production.up.railway.app/
  * Node Name: `https://tfctest-003-production.up.railway.app/`
  * Method: `GET`
  * Parameter: `Header User-Agent`
  * Attack: `Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)`
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/%3F_rsc=tXyZJ52UQVBCVsD3
  * Node Name: `https://tfctest-003-production.up.railway.app/ (_rsc)`
  * Method: `GET`
  * Parameter: `Header User-Agent`
  * Attack: `Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 6.0)`
  * Evidence: ``
  * Other Info: ``
* URL: https://tfctest-003-production.up.railway.app/%3F_rsc=tXyZJ52UQVBCVsD3
  * Node Name: `https://tfctest-003-production.up.railway.app/ (_rsc)`
  * Method: `GET`
  * Parameter: `Header User-Agent`
  * Attack: `Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)`
  * Evidence: ``
  * Other Info: ``

Instances: Systemic


### Solution



### Reference


* [ https://owasp.org/wstg ](https://owasp.org/wstg)



#### Source ID: 1


