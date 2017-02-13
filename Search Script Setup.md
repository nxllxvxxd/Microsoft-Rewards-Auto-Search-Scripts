You Can Find How To Set It Up Here

You Can Copy And Paste The Code Below Multiple Times If You Want To Use Multiple Accounts

To add multiple emails under 'Login Variables add more in this fashion:

`SET secondEmail bob@bob.com`
`SET secondPassword steve`
`SET thirdEmail steve@steve.com`
`SET thirdPassword bob`



All You Will Have To Do Is Play The Macro Everyday Because There Is No Way To Make It Run Automatically

`'Login Variables`

`SET firstEmail` PUTEMAILHERE

`SET firstPassword` PUTPASSWORDHERE

`'Website Variables`

SET signOut https://login.live.com/logout.srf?ct=1478526940&rver=6.7.6631.0&lc=1033&id=264960&ru=http:%2F%2Fwww.bing.com%2Fpassport.aspx%3Frequrl%3Dhttp%253a%252f%252fwww.bing.com%252f%253fwlexpsignin%253d1

SET signIn https://login.live.com/login.srf?wa=wsignin1.0&rpsnv=13&ct=1478526960&rver=6.7.6631.0&wp=MBI&wreply=https%3a%2f%2fwww.bing.com%2fsecure%2fPassport.aspx%3frequrl%3dhttp%253a%252f%252fwww.bing.com%252f%253fwlexpsignin%253d1&lc=1033&id=264960

SET mobileUseragent "Mozilla/5.0 (Windows Phone 10.0; Android 4.2.1; NOKIA; Lumia 735) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/39.0.2171.71 Mobile Safari/537.36 Edge/12.0"

SET defaultUseragent "Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2840.99 Safari/537.36"

SET  youtube http://www.bing.com/search?FORM=U312DF&PC=U312&q=youtube

SET googleGlass http://www.bing.com/search?FORM=U312DF&PC=U312&q=google+glass

SET googlePixel http://www.bing.com/search?FORM=U312DF&PC=U312&q=google+pixel

SET gmail http://www.bing.com/search?FORM=U312DF&PC=U312&q=gmail

SET xfinity http://www.bing.com/search?FORM=U312DF&PC=U312&q=xfinity

SET chrome http://www.bing.com/search?FORM=U312DF&PC=U312&q=chrome

SET starWars http://www.bing.com/search?FORM=U312DF&PC=U312&q=star+wars

SET eminem http://www.bing.com/search?FORM=U312DF&PC=U312&q=eminem

SET drDre http://www.bing.com/search?FORM=U312DF&PC=U312&q=dr+dre

SET yelawolf http://www.bing.com/search?FORM=U312DF&PC=U312&q=yelawolf

SET daylightSavings http://www.bing.com/search?FORM=U312DF&PC=U312&q=why+does+the+us+still+observe+daylight+savings+time

SET whatIsAuserAgent http://www.bing.com/search?FORM=U312DF&PC=U312&q=what+is+a+useragent

SET darth4212 http://www.bing.com/search?FORM=U312DF&PC=U312&q=darth4212

SET nintendo http://www.bing.com/search?FORM=U312DF&PC=U312&q=nintendo

SET familyGuy http://www.bing.com/search?FORM=U312DF&PC=U312&q=family+guy

SET wikipedia http://www.bing.com/search?FORM=U312DF&PC=U312&q=wikipedia

SET ununpentium http://www.bing.com/search?FORM=U312DF&PC=U312&q=ununpentium

SET wierdestElements http://www.bing.com/search?FORM=U312DF&PC=U312&q=wierdest+elements

SET appleEarpods http://www.bing.com/search?FORM=U312DF&PC=U312&q=apple+earpods

SET adsense http://www.bing.com/search?FORM=U312DF&PC=U312&q=adsense

SET daktech http://www.bing.com/search?FORM=U312DF&PC=U312&q=daktech

SET intelDrivers http://www.bing.com/search?FORM=U312DF&PC=U312&q=intel+drivers

SET windows10 http://www.bing.com/search?FORM=U312DF&PC=U312&q=windows+10

SET cortana http://www.bing.com/search?FORM=U312DF&PC=U312&q=cortana

SET microsoftEdge http://www.bing.com/search?FORM=U312DF&PC=U312&q=microsoft+edge

SET callOfduty http://www.bing.com/search?FORM=U312DF&PC=U312&q=call+of+duty

SET androidIphone http://www.bing.com/search?FORM=U312DF&PC=U312&q=why+android+is+better+than+iphone

SET steam http://www.bing.com/search?FORM=U312DF&PC=U312&q=steam

SET d12 http://www.bing.com/search?FORM=U312DF&PC=U312&q=d12

SET badMeetsevil http://www.bing.com/search?FORM=U312DF&PC=U312&q=bad+meets+evil

SET bing http://www.bing.com/

'Macro

URL GOTO={{bing}}

WAIT SECONDS= 2

URL GOTO={{signOut}}

WAIT SECONDS= 2

URL GOTO={{signIn}}

WAIT SECONDS= 2

TAG POS=1 TYPE=INPUT:EMAIL FORM=ID:i0281 ATTR=ID:i0116 CONTENT={{firstEmail}}

TAG POS=1 TYPE=INPUT:SUBMIT FORM=ID:i0281 ATTR=ID:idSIButton9

WAIT SECONDS= 2

SET !ENCRYPTION NO

TAG POS=1 TYPE=INPUT:PASSWORD FORM=ID:i0281 ATTR=ID:i0118 CONTENT={{firstPassword}}

TAG POS=1 TYPE=INPUT:SUBMIT FORM=ID:i0281 ATTR=ID:idSIButton9

WAIT SECONDS= 2

TAG POS=1 TYPE=INPUT:SEARCH FORM=ID:sb_form ATTR=ID:sb_form_q CONTENT=alpha

WAIT SECONDS= 2

TAG POS=1 TYPE=INPUT:SUBMIT FORM=ID:sb_form ATTR=ID:sb_form_go

WAIT SECONDS= 2

URL GOTO={{youtube}}

WAIT SECONDS= 4

URL GOTO={{googleGlass}}

WAIT SECONDS= 4

URL GOTO={{googlePixel}}

WAIT SECONDS= 4

URL GOTO={{gmail}}

WAIT SECONDS= 4

URL GOTO={{xfinity}}

WAIT SECONDS= 4

URL GOTO={{chrome}}

WAIT SECONDS= 4

URL GOTO={{starWars}}

WAIT SECONDS= 4

URL GOTO={{eminem}}

WAIT SECONDS= 4

URL GOTO={{drDre}}

WAIT SECONDS= 4

URL GOTO={{yelawolf}}

WAIT SECONDS= 4

URL GOTO={{daylightSavings}}

WAIT SECONDS= 4

URL GOTO={{whatIsAuserAgent}}

WAIT SECONDS= 4

URL GOTO={{darth4212}}

WAIT SECONDS= 4

URL GOTO={{nintendo}}

WAIT SECONDS= 4

URL GOTO={{familyGuy}}

WAIT SECONDS= 4

URL GOTO={{wikipedia}}

WAIT SECONDS= 4

URL GOTO={{ununpentium}}

WAIT SECONDS= 4

URL GOTO={{wierdestElements}}

WAIT SECONDS= 4

URL GOTO={{appleEarpods}}

WAIT SECONDS= 4

URL GOTO={{adsense}}

WAIT SECONDS= 4

URL GOTO={{daktech}}

WAIT SECONDS= 4

URL GOTO={{intelDrivers}}

WAIT SECONDS= 4

URL GOTO={{windows10}}

WAIT SECONDS= 4

URL GOTO={{cortana}}

WAIT SECONDS= 4

URL GOTO={{microsoftEdge}}

WAIT SECONDS= 4

URL GOTO={{callOfduty}}

WAIT SECONDS= 4

URL GOTO={{androidIphone}}

WAIT SECONDS= 4

URL GOTO={{steam}}

WAIT SECONDS= 4

URL GOTO={{d12}}

WAIT SECONDS= 4

URL GOTO={{badMeetsevil}}

SET !USERAGENT {{mobileUseragent}}

URL GOTO={{bing}}

TAG POS=1 TYPE=INPUT:SEARCH FORM=ID:sb_form ATTR=ID:sb_form_q CONTENT=alpha

WAIT SECONDS= 2

TAG POS=1 TYPE=INPUT:SUBMIT FORM=ID:sb_form ATTR=ID:sbBtn

WAIT SECONDS= 2

URL GOTO={{youtube}}

WAIT SECONDS= 4

URL GOTO={{googleGlass}}

WAIT SECONDS= 4

URL GOTO={{googlePixel}}

WAIT SECONDS= 4

URL GOTO={{gmail}}

WAIT SECONDS= 4

URL GOTO={{xfinity}}

WAIT SECONDS= 4

URL GOTO={{chrome}}

WAIT SECONDS= 4

URL GOTO={{starWars}}

WAIT SECONDS= 4

URL GOTO={{eminem}}

WAIT SECONDS= 4

URL GOTO={{drDre}}

WAIT SECONDS= 4

URL GOTO={{yelawolf}}

WAIT SECONDS= 4

URL GOTO={{daylightSavings}}

WAIT SECONDS= 4

URL GOTO={{whatIsAuserAgent}}

WAIT SECONDS= 4

URL GOTO={{darth4212}}

WAIT SECONDS= 4

URL GOTO={{nintendo}}

WAIT SECONDS= 4

URL GOTO={{familyGuy}}

WAIT SECONDS= 4

URL GOTO={{wikipedia}}

WAIT SECONDS= 4

URL GOTO={{ununpentium}}

WAIT SECONDS= 4

URL GOTO={{wierdestElements}}

WAIT SECONDS= 4

URL GOTO={{appleEarpods}}

WAIT SECONDS= 4

URL GOTO={{adsense}}

WAIT SECONDS= 4

URL GOTO={{daktech}}

WAIT SECONDS= 4

URL GOTO={{intelDrivers}}

WAIT SECONDS= 4

URL GOTO={{windows10}}

WAIT SECONDS= 4

URL GOTO={{cortana}}

WAIT SECONDS= 4

URL GOTO={{microsoftEdge}}

WAIT SECONDS= 4

URL GOTO={{callOfduty}}

WAIT SECONDS= 4

URL GOTO={{androidIphone}}

WAIT SECONDS= 4

URL GOTO={{steam}}

WAIT SECONDS= 4

URL GOTO={{d12}}

WAIT SECONDS= 4

URL GOTO={{badMeetsevil}}

SET !USERAGENT {{defaultUseragent}}

