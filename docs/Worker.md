# Worker


## این روش منسوخ شده است. از روش های دیگر استفاده کنید

همانطور که می دونید کلودفلیر به هر دلیلی استفاده از پراکسی رو در ورکر ها و page اش غیر قانونی اعلام کرده است. نخست ما باید سپاسگزار کلودفلیر باشیم برای اینکه توی این سالها به دسترسی ایرانیان به اینترنت_آزاد کمک شایانی کردند.
لذا من روش های که با ورکر هستند مثل پنل BPB و پنل وحید رو منسوخ شده اعلام می کنم ولی این روش ها رو از دانشنامه پاک نمی کنم. علتش اینکه آیندگان باید بدانند که برای دسترسی به اینترنت_آزاد چه تلاش هایی انجام شده است و چه استعدادهای وقت خودشون برای آزادی به صرف کردند.

اگر هم الان سوالتون این هست پس چجوری وصل بشیم، روش های مستقیم و تانل و استارلینک، سه دسته اصلی اتصال هستند.

https://filtershekan.sbs/Direct/

https://filtershekan.sbs/Internal_Server/

https://filtershekan.sbs/Starlink/




## مقدمه


سرویس‌های VPN، بر روی اره فیلترینگ و تحریم کلودفلر

در هفته اخیر گزارش‌های متعددی درخصوص به مشکل برخوردن میزبانی VPNها، عمدتا بر روی سرویس pages/workers کلودفلر مطرح شده بود، که برخی از کاربران با انتقال دامنه خود به یک اکانت جدید، برخی با شارژ دلاری حساب و برخی توسط پیگیری از طریق سامانه پشتیبانی کلودفلر، مشکل رو به طور موقت حل کردن.

کلودفلر در پاسخ به پیگیری کاربرانی که با مشکل مواجه شدن، گفته در آینده نزدیک قوانین مربوط به مسدودسازی اکانت‌هایی که در دسته‌بندی v2ray یا VPN قرار بگیرن طی یک فرایند خودکار صورت میگیره، که این‌دسته که بخش وسیعی از فعالیت کاربران ایرانی رو بر روی این‌سرویس شامل میشه، به تعبیری مشمول تحریم خواهند شد.

از طرف دیگه، امروز IR-GFW که وضعیت اختلال‌های اینترنت ایران رو مورد بررسی قرار میده، از فیلتر شدن مجدد سرویس pages کلودفلر خبر داده، که پیش‌تر نیز شاهد این‌مساله و رفع فیلتر اون بودیم.



خلاصه‌ای از روش‌های اصلی توصیف شده برای دور زدن فیلترینگ اینترنت را ارائه می‌دهم:

1. ورکرهای کلودفلر: استفاده از پلتفرم سرورلس کلودفلر برای ایجاد سرویس‌های شبیه VPN. اسکریپت‌ها و پیکربندی‌های مختلفی برای راه‌اندازی v2ray، تروجان و سایر پروتکل‌ها روی ورکرها به اشتراک گذاشته شده است.

2. صفحات کلودفلر: مشابه ورکرها، اما با استفاده از سرویس میزبانی سایت استاتیک کلودفلر برای استقرار سرورهای پروکسی.

3. EDtunnel/Edge Tunnel: یک پیاده‌سازی خاص برای ورکرهای کلودفلر که پیکربندی‌های VLESS ایجاد می‌کند.

4. ربات‌های تلگرام: چندین پروژه که به کاربران اجازه می‌دهد از طریق ربات‌های تلگرام، پیکربندی‌های VPN را ایجاد و مدیریت کنند، اغلب با ورکرهای کلودفلر یکپارچه شده‌اند.

5. SingBox: ابزاری که می‌تواند با ورکرهای کلودفلر برای دسترسی به سایت‌های فیلتر شده در پلتفرم‌های مختلف (اندروید، مک، iOS، ویندوز) ترکیب شود.

6. BBPB: نسخه بهینه‌شده‌ای از یک راه‌حل مبتنی بر کلودفلر برای دسترسی به سایت‌های مسدود شده.

7. ابزارهای اسکن IP: روش‌هایی برای یافتن IP‌های "تمیز" کلودفلر برای استفاده با تنظیمات مختلف VPN.

8. Bepass: یک افزونه برای NekoBox (یک اپلیکیشن اندروید) که با پیکربندی خاصی از ورکر کلودفلر کار می‌کند.

9. تولیدکننده‌های لینک اشتراک: ابزارهایی برای ایجاد لینک‌های اشتراک پر از پیکربندی‌های مختلف VPN، هم مبتنی بر ورکر و هم غیر ورکر.

این روش‌ها عموماً بر زیرساخت کلودفلر برای دور زدن فیلترینگ تکیه دارند و اغلب از اسکریپت‌های سفارشی مستقر شده به عنوان ورکرها یا صفحات استفاده می‌کنند. آنها معمولاً نیازی به سرور شخصی ندارند، که آنها را برای مخاطبان گسترده‌تری قابل دسترس می‌کند. با این حال، مهم است توجه داشته باشیم که اثربخشی این روش‌ها می‌تواند متفاوت باشد و ممکن است با گذشت زمان و تکامل تکنیک‌های فیلترینگ تغییر کند.



##  آموزش رفع ارور 1101 ورکر کلودفلر با کد جدید (فیلترشکن رایگان کلودفلر) 🔥 

ویدیو آموزش رفع ارور 1101 ورکر کلودفلر با کد جدید (فیلترشکن رایگان کلودفلر) آماده شده و امیدوارم بتونه تا حدودی از مشکلات شما کم کنه. اگه بازم این روش رو بستن روش دیگه ای براتون پیدا میکنیم. برای حمایت از ما لطفا از اسپانسرهای ما حمایت کنید.


ارور 1101 کلودفلر و حل مشکل ارور ورکر و ساخت فیلترشکن در کلودفلر و اینکه این پاراگراف چندی از کلمات کلیدی این ویدیو هستش :)


با حمایت کردن من توسط سابسکرایب و لایک و کامنت منو تو ادامه مسیر همراهی کنید :)

https://www.youtube.com/watch?v=o5VxvU8wfXo


## Obfuscation

بچه‌ها برای مبهم سازی کد ورکر می‌تونید از این وبسایت استفاده کنید 

http://obfuscator.io

مثلاً کد ورکر وحید را بهش بدید بعد از خروجی برای ساخت ورکر استفاده کنید من با کد وحید تست کردم مثل مرد کار می‌کنه😉 احتمالا به اسم کلمه vless و trojan داخل کد حساس هستش

## worker

[کد جدید ورکر v2ray (نسخه ۲.۳) آماده شد و میتونید به سادگی برای خودتون یک vpn رایگان بسازید.](https://twitter.com/vahidfarid/status/1772998305493967116)

[کد آپدیت شده‌ی ورکر تولید ساب برای کلاینت‌های v2ray رو آپدیت کردم و میتونید از روی گیت‌هاب نسخه‌ی ۱.۷ رو دریافت و روی ورکرهاتون جایگزین کنید.](https://threadreaderapp.com/thread/1656027952746823681.html)

[ ساخت فیلترشکن رایگان بدون سرور و دامین با استفاده از ورکر Cloudflare-Worker ](https://www.youtube.com/watch?v=9v57JYYn-Ww)

[امروز میخوام یه داستان بگم برای کسانی که میخوان vpn یا کانفیگ خودشون رو درست کنن و نمیدونن از کجا شروع کنن؟](https://threadreaderapp.com/thread/1639220465477492738.html)

[cf-ip-scanner](https://vfarid.github.io/cf-ip-scanner/)

[راهکار جامع کانفیگ‌های v2ray روی ورکر](https://github.com/vfarid/v2ray-worker/blob/main/README-fa.md)

[v2ray-worker](https://github.com/vfarid/v2ray-worker)

[کانال وحید](https://www.youtube.com/@vahidfarid)


[EDtunnel](https://github.com/3Kmfi6HP/EDtunnel)

[ Cloudflare Pages to easily deploy v2ray proxy, no server required & extremely fast! Step-by-step! ](https://www.youtube.com/watch?v=8I-yTNHB0aw)


[آموزش cloudflare pages برای اولین بار برای عبور از فیلترینگ با سرعت بالا+ای پی تمیز+فرگمنت کردن کانفیگ](https://telegra.ph/%D8%A2%D9%85%D9%88%D8%B2%D8%B4-cloudflare-pages-%D8%A8%D8%B1%D8%A7%DB%8C-%D8%A7%D9%88%D9%84%DB%8C%D9%86-%D8%A8%D8%A7%D8%B1-%D8%A8%D8%B1%D8%A7%DB%8C-%D8%B9%D8%A8%D9%88%D8%B1-%D8%A7%D8%B2-%D9%81%DB%8C%D9%84%D8%AA%D8%B1%DB%8C%D9%86%DA%AF-%D8%A8%D8%A7-%D8%B3%D8%B1%D8%B9%D8%AA-%D8%A8%D8%A7%D9%84%D8%A7%D8%A7%DB%8C-%D9%BE%DB%8C-%D8%AA%D9%85%DB%8C%D8%B2%D9%81%D8%B1%DA%AF%D9%85%D9%86%D8%AA-%DA%A9%D8%B1%D8%AF%D9%86-%DA%A9%D8%A7%D9%86%D9%81%DB%8C%DA%AF-02-20)


[رازهای اتصال به اینترنت آزاد: آشنایی با چندین روش موثر و کارآمد رایگان](https://www.youtube.com/watch?v=l3hAVwk13ic)


## کلودفلیر

[ آموزش کامل کلودفلر و ایجاد ساب دامنه بی نهایت (فرار از فیلترینگ) ](https://www.youtube.com/watch?v=BM3T_8qKcuo)


## EDtunnel or Edge Tunnel 

[amin](https://twitter.com/amin_o__o/status/1766080891544027145)
بعد بچه‌ها از این کد برای ورکر استفاده کنید
انتهای کد تعداد زیادی آدرس وبسایت های چینی هستش همه را پاک کنید مثل عکس آدرس های ایرانی بزنید من تست کردم ping کمتر میشه البته تست که روی این اینترنت ت.خ معنی نداره

[worker](https://github.com/3Kmfi6HP/EDtunnel/blob/main/_worker.js)


[ بدون داشتن سرور و با Edge Tunnel کانفیگ Vless بساز و محدودیت کلودفلر رو دور بزن ](https://www.youtube.com/watch?v=3XoiNd3CNts)


## EDtunnel

https://github.com/iPsycho1/EDtunnel

EDtunnel 是一个基于 Cloudflare Workers 和 Pages 的代理工具，支持多种协议和配置选项。

EDtunnel is a proxy tool based on Cloudflare Workers and Pages, supporting multiple protocols and configuration options.

## CFW-BOT

میتونید این ربات تلگرامی رو بدون نیاز به سرور  برای خودتون نصب و اجرا کنید تا بدون دردسر براتون کانفیگ xray با ورکر کلادفلر بسازه
و میتونید داخلش کاربران ورکر رو مدیریت کنید 

[ فیلترشکن شخصی - CFW-BOT -نصب و اجرا بات رایگان تلگرامی XRAY با ورکر کلادفلر - بدون نیاز به سرور ! ](https://www.youtube.com/watch?app=desktop&v=ejgTbf_yJJQ)

[CFW-BOT](https://github.com/2ri4eUI/CFW-BOT)

درود
گفتید ویدیو آموزش نصب ربات ورکر کلاد فلر رو بساز 
خدمت شما ✌️
✅ فقط با کپی یک خط کد!
✅بدون نیاز به سرور
✅بدون نیاز به دامین
✅با یک ایمیل موقت!
✅با مرورگر موبایل !

[twitter](https://x.com/ghostofnikaas/status/1793330355958673773)


## ورکر کلودفلر با قابلیت ساخت کاربر و مدیریت از طریق ربات تلگرام

آیا می‌خواهید یک ورکر کلودفلر قدرتمند را بسازید که به کمک آن بتوانید کاربران خود را به راحتی ایجاد کرده و از طریق ربات تلگرام مدیریت کنید؟ در این ویدیو، به شیوه‌نامه‌ای جامع و قدم به قدم آموزش داده می‌شود که چگونه ورکر کلودفلر را ایجاد کرده و امکان ساختن و مدیریت کاربران از طریق ربات تلگرام را فراهم کنید.

در این دوره آموزشی، ابتدا با مفاهیم اساسی ورکر کلودفلر آشنا می‌شوید و سپس با استفاده از ابزارها و تکنیک‌های مربوط، یک ورکر کلودفلر کامل و عملی را ایجاد خواهید کرد. سپس، با استفاده از ربات تلگرام، که یکی از محبوب‌ترین پلتفرم‌های پیام‌رسانی است، خواهید دید که چگونه می‌توانید به کمک آن کاربران را ایجاد کرده و مدیریت کنید.

با تماشای این ویدیو، شما قادر خواهید بود تا مهارت‌های لازم برای ایجاد و مدیریت ورکر کلودفلر خود را به دست آورید و از این طریق ارتقاء و بهبود کسب و کار خود را تجربه کنید. آماده‌اید؟ با ما همراه باشید و این ابزارهای قدرتمند را به کار بگیرید.


[ورکر کلودفلر با قابلیت ساخت کاربر و مدیریت از طریق ربات تلگرام](https://www.youtube.com/watch?v=T8euPf2RAos)



## آیفون


سلام اینم آموزشی که قولش رو داده بودم که باهاش میتونید با چندین مرحله ساده و بدون نیاز به سرور و با آیفونتون برای خودتون فیلترشکن رایگان بسازید , در نهایت شما یک لینک ساب دریافت میکنید که میتونید با تمام برنامه هایی که لینک سابسکریپشن رو پشتیبانی میکنن ازش استفاده کنید 

نکته اینکه اصلا ازش برای ترید استفاده نکنید چون داره خودکار به بهترین سرور وصل میشه و آیپی تغییر میکنه 

مورد دوم اینکه سایت های که پشت کلودفلر هستند رو ممکنه باز نکنه که در ویدیوهای بعدی این مشکل رو هم با هم حل میکنیم 

[ ساخت VPN رایگان با آیفون (بدون نیاز به سرور) - مناسب تمامی شبکه های اجتماعی - قسمت اول ](https://www.youtube.com/watch?v=2Gi0gjVsjos)


##  ساخت کانفیگ ویتوری |v2ray| به صورت کاملا رایگان و تضمینی اتصال روی همه اپراتور ها 

در این ویدیو به شما آموزش میدیم چطور بدون نیاز به دانش فنی و فقط با داشتن یک گوشی موبایل یا کامپیوتر و ثبت نام ساده در سایت کلودفلر یک کانفیگ ویتوری کاملا رایگان و نامحدود برای خودتون یا اطرافیانتون بسازید و به اینترنت آزاد متصل بشید.
این روش کاملا تضمینی و تست شده است و اگر طبق ویدیو مراحل رو انجام بدید به راحتی میتونید یک کانفیگ ویتوری به صورت کاملا رایگان و نامحدود ایجاد کنید

[ ساخت کانفیگ ویتوری |v2ray| به صورت کاملا رایگان و تضمینی اتصال روی همه اپراتور ها ](https://www.youtube.com/watch?v=f0vziSaHRzM)


## توی این ویدیو، بهتون آموزش میدم که چطور یک پنل VPN ساده و کارآمد رو روی ورکرهای رایگان Cloudflare راه اندازی کنید.

[ آموزش ساخت vpn اختصاصی ( رایگان - ضدفیلتر) ](https://www.youtube.com/watch?v=dl5VR7jA8dk)



## آموزش استفاده از ورکر +singbox برای عبور از فیلترینگ اندروید و مک و ios و ویندوز

ترکیب cloudflare worker+singbox برای دسترسی به سایتهای فلیترشده(پالایش شده😍) و تحریم شده
به اشتراک بذارید همه استفاده کنن
آموزش تا اخر ببینید تو فایل json اندروید قسمت host باید ادرس ورکر وارد کنید .

[link](https://telegra.ph/%D8%A2%D9%85%D9%88%D8%B2%D8%B4-%D8%A7%D8%B3%D8%AA%D9%81%D8%A7%D8%AF%D9%87-%D8%A7%D8%B2-%D9%88%D8%B1%DA%A9%D8%B1-singbox-%D8%A8%D8%B1%D8%A7%DB%8C-%D8%B9%D8%A8%D9%88%D8%B1-%D8%A7%D8%B2-%D9%81%DB%8C%D9%84%D8%AA%D8%B1%DB%8C%D9%86%DA%AF-%D8%A7%D9%86%D8%AF%D8%B1%D9%88%DB%8C%D8%AF-%D9%88-%D9%85%DA%A9-%D9%88-ios-04-28)


## ساخت کانفیگ trojan worker بر پایه cloudflare worker

تا حالا ازvless یا vmess استفاده می کردیم الان پروتکل trojan هم اضافه شد .دسترسی به سایتهای پالایش شده و تحریم شده😍😍

[twitter](https://threadreaderapp.com/thread/1787037425165819985.html)

https://twitter.com/horizonbehind2/status/1787109656449462724

رمز به سایت میدن hash بسازه
hash میشه رمز ورکر
حروفی که خودشون میدن میشه رمز کانفیگ

## استفاده ترکیبی از singbox ,cloudflare worker

برای دسترسی به سایتهای  تحریم و پالایش شده😚😚
با توجه به اختلالات شدید
ممکنه برای بعضی ها singbox کانفیگ کار نکنه
دوستان صاحب نظر می تونند کد بهینه کنند 

[twitter](https://threadreaderapp.com/thread/1788484810790334646.html)


## اموزش ساخت کانفیگ Trojan روی Worker سایت Cloudflare

[youtube](https://www.youtube.com/shorts/H33KkfkJoMo)

[worker.js](https://github.com/cmliu/epeius/blob/main/_worker.js)


## اختلال کلودفلیر

روی ورکر  اختلال شدید هست
من یک تستی کردم روی اسیا تک و مخابرات  اختلال تا حد بسیار زیادی کاهش داد تقریبا شده مثل قبل  براتون جواب بده  جواب نده
قسمت dohurl کدتون داره
اون قسمت به جای rethink بزارید
کار نکرد از dns های شکل همه با h3 شروع میشن

[twitter](https://twitter.com/horizonbehind2/status/1791153153091453253)


##  BBPB کلودفلر 

نسخه بهینه شده BBPB کلودفلر برای دسترسی به سایتهای  تحریم و پالایش شده.دوستی  تو گیت هاب زحمتش کشید من فقط آموزشش گذاشتم.


[twitter](https://threadreaderapp.com/thread/1799445532953514260.html)



## حل مشکل پیدا کردن ای پی تمیز برای تمامی پنلهای ورکر کلودفلر دارای نسخه ویندوزی و اندرویدی


حل مشکل پیدا کردن ای پی تمیز برای تمامی پنلهای ورکر کلودفلر دارای نسخه ویندوزی و اندرویدی
ای پی مناسب با دسته بندی پینگ
بار اول اجرا یک طول میکشه وقت میبره


https://threadreaderapp.com/thread/1821626840911401031.html



## ساخت کانفیگ توسط ورکر bepass uoosef 

ساخت کانفیگ توسط ورکر bepass uoosef 


۱.‌ از یکی از لینک های زیر پلاگین bepass رو دانلود کنید

•  https://github.com/bepass-org/nekobepass/releases

•  https://fdroid.noql.net/

۲. پلاگین رو داخل برنامه نکوباکس (https://github.com/MatsuriDayo/NekoBoxForAndroid/releases) فعال کنید 

۳. وارد لینک زیر بشید و فایل worker (https://github.com/bepass-org/bepass-worker/blob/main/dist/worker.js) رو دانلود کنید

• https://github.com/bepass-org/bepass-worker

۴. به کلودفلر (https://dash.cloudflare.com/) برید و یک ورکر بسازید وفایل رو داخلش اپلود کنید

۵. ورکر خودتون رو در فرمت زیر قرار دهید 

https://name.workers.dev/dns-query

• /dns-query 

۶. فایل خامی که باید در اخر ادرس worker خودتونو داخلش قرار بدید  داخل لینک زیر هستش 


• https://rentry.co/bepass
چنتا کانفیگ آماده هم برای استفاده هست 

آموزشای بیشتر.... (https://t.me/darkness_427)

https://t.me/darkness_427/223



## ساخت لینک سابهای مختلف پر از کانفیگهای متفاوت چه بر پایه ورکر و چه غیرورکر با استفاده از کد جدید ورکر

 ساخت لینک سابهای مختلف پر از کانفیگهای متفاوت چه بر پایه ورکر و چه غیرورکر با استفاده از کد جدید ورکر
فیلترشکن  فیلترنت  اینترنت_آزاد Image
ابتدا وارد سایت بشین و یک اکانت درست کنید سپس از قسمت worker and pages یک ور کر می سازیم و edit می زنیم
و از لینک زیر کد کپی وارد و deploy کنید

بعد با عکس طبق صفحه سوم مواجه می شوید
فیلترنت dash.cloudflare.com

https://github.com/mostafa1950/workervpn/blob/main/worker


https://threadreaderapp.com/thread/1828093180816081314.html


##  نحوه ایجاد لینک ساب VPN با ورکر و IP تمیز 

https://www.youtube.com/watch?v=B22IDxlpNHk

##  آموزش کامل آیپی تمیز و ساخت کانفیگ v2ray رایگان_SIXTININELEARN 

سلام رفقا توی این ویدیو قراره بهتون یاد بدم چجوری خیلی راحت با استفاده تانلGRE6TAP بین سرور ایران و خارجتون یه تانل پایدار برقرار کنین.

https://www.youtube.com/watch?v=vgJSvbR0GXQ