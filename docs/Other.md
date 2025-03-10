# Other

خلاصه‌ای از روش‌ها و ابزارهای ذکر شده برای دسترسی به اینترنت و دور زدن فیلترینگ به فارسی است:

راه حل اسپاتیفای: استفاده از دامنه و سرور، اجتناب از اشتراک‌گذاری تنظیمات با افراد زیاد. یک گزینه گران‌تر استفاده از NordVPN به عنوان لایه آخر تونل است.
ماتریکس/سیناپس: یک شبکه ارتباطی غیرمتمرکز و متن‌باز. می‌تواند خود‌میزبانی شود یا از طریق سرویس‌هایی مانند wiiz.ir استفاده شود.
Tailscale: یک VPN مدرن بر پایه WireGuard که یک شبکه مش نظیر به نظیر ایجاد می‌کند. نسبت به VPN‌های سنتی، توان عملیاتی بالاتر و تأخیر کمتری ارائه می‌دهد.
ChatGuard: یک افزونه مرورگر که رمزنگاری انتها به انتها برای پیام‌رسان‌های داخلی فراهم می‌کند و حریم خصوصی و امنیت را افزایش می‌دهد.
File Tunnel: ابزاری برای دور زدن فایروال‌ها با ایجاد اتصالات TCP از طریق فایل‌های مشترک بین سیستم‌ها.
تغییر رایگان موقعیت VPN: روشی برای تغییر موقعیت VPN به کشورهای مختلف به صورت رایگان.
ISP-Blocker: ابزاری برای مسدود کردن دسترسی ISP‌های خاص به سرور شما، افزایش امنیت.
NipoVPN: یک راه حل VPN (جزئیات بیشتری در خلاصه ارائه نشده است).
پروژه امید: ابتکاری برای ارائه دسترسی رایگان به اینترنت در ایران با ساده‌سازی و عمومی کردن دانش عبور از فیلترینگ.
IRAN_VPN_Guide_bot: یک ربات تلگرام که دستورالعمل‌های تخصصی تنظیم VPN برای XRay و V2Ray به زبان فارسی ارائه می‌دهد.
VPN سایفرپانک‌های ایرانی: گروهی با هدف ارائه دسترسی به اینترنت برای همه مردم، با تمرکز بر گسترش آزادانه اطلاعات.

این روش‌ها از راه‌حل‌های خود‌میزبانی تا افزونه‌های مرورگر و سرویس‌های VPN را شامل می‌شوند، همه با هدف دور زدن محدودیت‌های اینترنتی و افزایش حریم خصوصی و امنیت آنلاین.


## Spotify

برای حل مشکل اسپاتیفای باید از دامنه و سرور استفاده کنید
و این کانفیگ رو به افراد متعدد ندهید. یک راه گران هم خرید وی پی ان نورد و گذاشتن در لایه آخر تونل هست.

[nordvpn](https://nordvpn.com/)


## NordWhisper

پروتکل NordWhisper که توسط NordVPN توسعه داده شده بر اساس WebTunnel، به طور خاص برای جلوگیری از فیلترهای پیشرفته که جلوی VPN ها را میگیرد طراحی شده

https://nordvpn.com/blog/nordwhisper-protocol/

داخل app NordVPN app داخل تنظیمات هست
دنبال راهی برای راه اندازی شخصی هستم

![pic](https://pbs.twimg.com/media/GiiXG0RWEAAUmuk?format=jpg&name=small)

در موردش خوندم و به نظر میاد چیز جالبی باشه. هرچند فکر نکنم خیلی زیاد توی ایران عمر کنه و شاید بیشتر توی کشورهایی که فیلترینگ کمتری دارن بهتر عمل کنه. به هر حال، این شرکت‌ها که وارد این داستان میشن نشونه خوبیه

نوشته برای مبارزه با anti-VPN solutions برای کشورهای 
China, India, Pakistan, Russia
و تمرکز روی obfuscation techniques

https://nordvpn.com/blog/nordwhisper-protocol/


Introducing the NordWhisper protocol — a step towards a more open internet

At NordVPN, our goal is to ensure everyone has secure and reliable internet access, no matter where they are. Recognizing the challenges our users face when connecting to networks with restrictive policies, we’re introducing NordWhisper — a new protocol coming to the NordVPN app designed to make navigating these environments easier. Here’s everything you need to know about this protocol.


What is the NordWhisper protocol, and how does it work?

NordWhisper is a new NordVPN protocol designed specifically to allow users to connect to VPN servers from networks that usually limit traditional VPN traffic. As a solution for navigating around network restrictions, NordWhisper ensures a smoother and more consistent browsing experience, even in restrictive environments. 

So how does it work? NordWhisper is based on web tunnel technology, which operates differently from traditional VPN protocols like OpenVPN or WireGuard. Most VPN protocols have distinct characteristics, like specific traffic signatures and behaviors. These patterns can sometimes be recognized by network administrators, who may block them. While many protocols incorporate obfuscation techniques to counteract them, some network policies can still filter them out.

NordWhisper mimics regular web traffic, making it more difficult for network filters to identify it. Essentially, it blends in with ordinary internet activity, providing users with a reliable way to browse on restricted networks while maintaining the same strong encryption and security as other VPN protocols.
The background

We saw the need for a solution for users unable to connect to NordVPN in restrictive environments. This problem often results in disrupted work and limited access to essential services. To address these issues, we developed NordWhisper — a VPN protocol specifically designed to avoid advanced network filters.

While some networks may limit what you can access, we believe everyone deserves the ability to browse freely, safely, and without interruptions. This protocol is our latest step toward enabling a more open internet.

Even though NordWhisper makes access easier and more convenient, it upholds the same strong security and privacy standards that NordVPN is known for. You can trust that your internet traffic will remain private and protected, no matter which protocol you choose.
When does the NordWhisper protocol come into play?

The new NordWhisper protocol is designed specifically for situations where traditional VPN protocols are blocked by advanced network filters. These filters are typically applied to prevent VPN usage and may be found in public Wi-Fi hotspots with security filters, like those at airports, cafes, conferences, or other locations with managed internet access.

While standard protocols using obfuscation techniques are effective on networks that prevent access to essential services or public resources, NordWhisper steps in when VPN-specific blocks make connecting to these networks more challenging. This protocol ensures users can browse securely in restricted networks.

Disclaimer: We do not support or encourage any illegal activities when using NordWhisper or any other protocol with NordVPN. Please ensure that your use of NordVPN complies with all applicable laws, agreements, and network policies.

However, while NordWhisper works great with network filters, it may be slower than other protocols in some circumstances due to the technology it uses. So if you’re connected to a regular network, we recommend sticking to other protocols. That said, the landscape of network filtering is constantly evolving, and we will continue to improve NordWhisper — making it smarter, faster, and more secure to keep up with these changes.
When will it be released?

We're gradually rolling out the NordWhisper protocol to ensure it performs at the standards our users expect. Initially, it will be available on Windows, Android, and Linux, with support coming to more platforms over time.

Once it’s available, you’ll find the option to manually select it within the VPN connection settings on the NordVPN app. So if you face connection issues due to network filters, try it out and see the difference.

Stay tuned for updates as we expand NordWhisper to more platforms.

https://nordvpn.com/blog/nordwhisper-protocol/

## Synapse 

Synapse is now actively maintained at element-hq/synapse 


Synapse is an open-source Matrix homeserver developed from 2019 through 2023 as part of the Matrix.org Foundation. The Matrix.org Foundation is not able to resource maintenance of Synapse and it continues to be developed by Element; additionally you have the choice of other Matrix homeservers.

See The future of Synapse and Dendrite blog post for more information.

[Synapse](https://github.com/matrix-org/synapse)


matrix 
An open network for secure, decentralised communication

[https://matrix.org/](https://matrix.org/)


[ A walk through of installing Synapse+Riot+Jitsi from scratch on Debian ](https://www.youtube.com/watch?v=dDddKmdLEdg)

بخش jitsi رو احتیاجی نیست نصب بشه. به جاش از coturn استفاده میشه. تو بخش doc میتونی تنظیمات رو ببینی

اگر رو سرور نصب بشه که هیچ. من رو دسکتاپ نصب کردم. ای پی ثابت میخواد و یک دومین برای  فعال کردن encryption


[ اتصال تلگرام بدون فیلتر شکن | پیامرسان ماتریکس | منبع کانفیگ v2rayng ویندوز ](https://www.youtube.com/watch?v=a4ndutthhuk)

ماتریکس و xmpp -> پیام رسان فدریتد
ماستادون -> توییتر فدریتد
ماتریکس به صورت دیفالت رمزنگاری دو طرفه داره و پیام های شما امن هست. همین در xmpp هم میتونه استفاده بشه (لزوما دیفالت فعال نیست)


[khiar.net](https://khiar.net/@sadraiiali/109745055218419870)



از اینکه ویز رو به عنوان خونه‌ی ماتریکسی خودتون انتخاب کردید خیلی خوشحالیم. ما یک گروه کوچیکیم که به دنبال تشویق فرهنگ استفاده از خدمات غیرمتمرکز و آزاده. شما هم مثل ما می‌تونید با دوست‌هاتون شریک بشید و سرور تماس تصویری و چت امن خودتون رو داشته باشید، یا از همین ویز استفاده کنید. ولی به هر حال منابع ما محدوده و اخیرا که مراجع‌های بیشتری داریم کیفیت خدماتمون تحت تاثیر قرار گرفته؛ در حال خرید منابع بیشتر برای رفع مشکل هستیم.


[wiiz.ir](https://wiiz.ir/)


[ آموزش دور زدن فیلترینگ با استفاده از پل ماتریکس | ضد فیلترکردن شبکه های اجتماعی ](https://www.youtube.com/watch?v=LDtA00cbaes)


[ اتصال به پیام رسان های فیلتر بدون فیلتر شکن برای همه پلت فرم ها ](https://www.youtube.com/watch?v=pebM_cHAlQk)


سلام رفقا در مورد Beeper ی نکته اینکه پیامها قبل از ارسال با E2EE رمزنگاری میشه 
هنوز هیچ گزارش مشکوک و منفی در مورد beeper گزارش نشده 

شخصا خودم استفاده میکنم 
اینکه تلگرام ، واتساپ، دایرکت توییتر ،اینستاگرام همه در یک محل بدون فیلتر اجرا بشه خیلی عالیه


## تفاوت VPN های سنتی با Tailscale چیه؟


نرم افزار Tailscale یک VPN مدرنه که روی WireGuard یک
به صورت یک Overlay network(شبکه‌های همپوشان) با NAT traversal یک شبکه مش نظیر به نظیر (tailnet) ایجاد می کنه Tailscale با دوری کردن از centralization مقدارthroughput بالاتر و latency کمتر داره
جا نیست،توضیح بیشتر کانال تلگرام😉



نرم افزار Tailscale ترکیب
open-source software-defined
mesh
virtual private network (VPN)
به عنوان یک VPN مدرنه روی پروتکل WireGuard یک شبکه مش نظیر به نظیر (tailnet) ایجاد می کنه Tailscale با دوری کردن از centralization مقدارthroughput بالاتر و latency کمتر به صورت یک Overlay network(شبکه‌های همپوشان) و با استفاده از NAT traversal در مجموع یک ارتباط امن برای شما ایجاد میکنه
پیاده سازی های مختلف روی سرور داره مثلا
https://github.com/juanfont/headscale
یک self-hosted implementation متن باز از Tailscale control server است

از اینجا دانلود کنید
https://tailscale.com/download

از اینجا اموزش بخونید
https://tailscale.com/kb/1017/install
گزینه های دیگه
https://openziti.io/
https://ferrumgate.com/
https://netbird.io/

[twitter](https://twitter.com/Mehrdadlinux/status/1780967017555845602)

[telegram](https://t.me/MehrdadLinuxchannel/449)

توضیح:
این ابزار خیلی خوبه، سال‌ها ازش استفاده میکنم. ولی تا جایی که می‌دونم، توی ایران کار نمیکنه. فکر نکنم زیاد به درد سایتتون بخوره.

اینو من خیلی وقته دارم، مشکل اینه روی خیلی از پروایدرها فیلتره و همونطور که دوستمون گفتن بر مبنای وایرگارده،

حالا اگه می‌شد اون ترکهای مارک و یوسف رو بهش اضافه کرد باز خوب بود



## Chat Guard

بیاین یکم پروژه چت‌گاردمون رو معرفی کنم.
چت‌گارد یه افزونه‌ست که با رمزنگاری E2E جلوی شنود اطلاعات رو توی پیامرسان‌های داخلی می‌گیره. یعنی باهاش می تونید توی بله، ایتا، سروش و... یه مکالمه کاملا امن [مثل مدل TLS] رو داشته باشید و پرایوسی شما حفظ بشه.

چت‌گارد رو میشه رو خود تلگرام هم فعال کرد. باهاش میشه توی قطعی اینترنت و شرایط خاص کشور ارتباط رو همراه پرایوسی حفظ کرد، یا توی هر حالت بدی که فیلترچی ما رو مجبور به استفاده از پیامرسان‌های داخلی کنه.

توی حالت فعلی باگی نداره ولی هنوز به نسخه پایدار نرسیده، ازتون می‌خوام یه نگاه بهش بندازید، تست کنید، از همه مهم‌تر مشارکت کنید و درآخر اگه قابل دونستید با ریتوییت و استار حمایت کنید چون واقعا برای به اینجا رسیدنش از چالش‌های خیلی سختی توی فرانت‌اند گذشتیم.


[ChatGuard](https://github.com/PrivacyForge/ChatGuard)

[video](https://twitter.com/MKheibary/status/1783224621300355220)


## file tunnel

دور زدن فیلترینگ فایروال:
با یک فایل Tunnel TCP connectionsبسازید😎
می خواهید از سیستم خودتان به نرم افزار یا سایت X متصل شوید، اما اتصال فیلتر شده. 
هر دو سیستم شما و مقصد به یک پوشه مشترک دسترسی دارند.😬 حله تمام
https://github.com/fiddyschmitt/File-Tunnel
ایده را دوست داشتم🥰، موقعیت تست نداشتم


https://github.com/fiddyschmitt/File-Tunnel




##  تعویض لوکیشن فیلترشکن به کشور های مختلف به صورت رایگان 


با یکی دیگه از ویدیوهای کاربردی به اسم تعویض لوکیشن فیلترشکن به کشور های مختلف به صورت رایگان در خدمت شما هستیم و امیدواریم این ویدیو هم مثل ویدیوهای دیگه براتون کاربردی باشه.


https://www.youtube.com/watch?v=wdgTL0i_JsY


## ISP-Blocker

 آموزش کامل ISP-Blocker و قطع دسترسی برخی اپراتور ها به سرور و کانفیگ ویتوری 


 در این ویدیو نحوه استفاده از IR-ISP-Blocker به شما اموزش میدیم تا بتوانید به راحتی دسترسی اپراتور مد نظرتون رو به سرورتون ببندید و امنیت سرورتون رو افزایش بدید.

 https://www.youtube.com/watch?v=N_XQ8Eq-cCA

 

## NipoVPN

 ویدیو آشنایی با NipoVPN رو رکورد کردم گذاشتم یوتیوب توش یه توضیح مختصری از کاری که میکنه دادم و همینطور یه تستی ازش گرفتم و اینکه مشکلاتی که داره رو هم توضیح دادم  دیگه همراهی کنید کمک کنید تا مشارکت انجام بشه و کامل‌تر بشه  

https://youtu.be/slAaPVnckE0
 کانال مرتضی باشسیز


## پروژه امید

ما در پروژه امید خواهان فراهم آوردن اینترنت آزاد برای همه ایران هستیم. هدف ما ساده‌سازی و همگانی کردن دانش عبور از فیلترینگ جمهوری اسلامی است. اینجا محفلی است برای به اشتراک گذاری تکنولوژی‌هایی که برای عبور از فیلترینگ حاکمیت ایران موثر هستند. هویت ما هیچگاه مشخص نخواهد شد و تا روز آزادی تلاش‌مان را برای گسترش اینترنت آزاد در ایران ادامه خواهیم داد.

[پروژه امید](https://github.com/iranxray/hope)


## بات تلگرام IRAN_VPN_Guide_bot

با درود
این مجموعه آموزش های و تنظیمات تخصصی اپلیکیشن های VPN مختص به XRay و V2Ray و به زبان فارسی برای کاربران ایرانی تهیه و تنظیم شده است.
</br>
هم یاد بگیریم و هم به بقیه یاد بدهیم
دست‌های هم رو بگیرید، تنهایی از این جا نمی‌تونیم گذر کنیم.
به امید پیروزی که خیلی دور نیست🤞🏽

[bot telegram](https://t.me/IRAN_VPN_Guide_bot)



## Stupid_risks

[Stupid_risks](https://linktr.ee/Stupid_risks)


## Iranian Cypherpunks VPN

[Ln2Ray](https://t.me/Ln2Ray)

هدف ما رسوندن اینترنت به همه مردم

تاریکی اصالت نداره، تاریکی در نبود نور شکل میگیره، اطلاعات آزاد در جایگاه نور این روزا

در حد توانمون نور میتابونیم به اطرافمون❤️