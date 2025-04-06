# LLM

## Remember Yousef llm telegram

telegram bot for serve a large language model

این پروژه به یاد یوسف قبادی ساخته شده است.

برای اجرا کردن این پروژه اول باید پروژه زیر را اجرا کنید:

https://github.com/majidrezarahnavard/remember_yousef_llm_serve

روی پورت ۸۰۸۰ سرویس اولاما اجرا شده است.
Bot Father

با استفاده از بات زیر یک کد اجرا باید بگیرید:

https://t.me/BotFather

.env
یک فایل .env بسازید و مثل .env.default مقدار توکن رو قرار دهید.

https://github.com/majidrezarahnavard/remember_yousef_llm_telegram


## remember Yousef llm serve

this repository make auto response based on Ollama 3.1 and way of freedom document

این پروژه به یاد یوسف قبادی ساخته شده است. ایده اصلی این هست که ما بتوانیم پاسخگویی و سرچ هوشمند روی مستندات دسترسی به اینترنت آزاد داشته باشیم.

این برنامه بر پایه اولا ساخته است و نیاز به داشتن GPU برای اجرا می باشد.

برای اجرا کردن برنامه دستورات زیر را پیروی کنید:

حتما باید داکر را روی سیسیتم نصب داشته باشید.

docker build -t llm-docs-ollama-app .

با دستور زیر تمامی داکر ها را اجرا کنید: فایل .env را به صورت دستی ایجاد کنید

sudo docker-compose up

حتما باید GPU روی سیستم شما نصب باشد با دستور زیر می توانید چک کنید

nvidia-smi -l 1

حالا شما باید مدل های اولاما رو دانلود کنید:

sudo docker-compose -f docker-compose.yml exec ollama /bin/sh 
ollama run nomic-embed-text
ollama run llama3.1

با ظاهر شدن پیغام زیر اولا روی پورت ۸۰۸۰ اجرا میشود

INFO:     Uvicorn running on http://0.0.0.0:8080 (Press CTRL+C to quit)



## DeepSeek

با این آموزش میتونید هوش مصنوعی DeepSeek رو به شکل لوکال و آفلاین روی لپ تاپتون اجرا کنید. اینطوری سانسور هم ندارید.
کلا به غیر از مرحله دانلود دیتا, ۲ دقیقه هم وقت نمیگیره.

خلاصش اینکه:
۱- از اینجا ollama رو دانلود کنید تا در نهایت cli رو نصب کنه واستون
https://ollama.com/download

۲- بعد که خط فرمان نصب شد, از هر ترمینالی که دارید یکی از این مدل هارو نصب کنید.
بهترینش همون 70b هست ولی سخت افزار خیلی قوی میخواید. جهت تست میتونید اولی رو بگیرید که حدود ۱ گیگ دانلود داره.
منم اولی رو فقط گرفتم بعد دونه دونه برم جلو ببینم چی برام جوابه😁

![pic](https://pbs.twimg.com/media/GiNqHA7WoAANNiU?format=jpg&name=small)

ستورات نصب مدل های مختلف:
1.5B version (smallest):
ollama run deepseek-r1:1.5b

8B version:
ollama run deepseek-r1:8b

14B version:
ollama run deepseek-r1:14b

32B version:
ollama run deepseek-r1:32b

70B version (biggest/smartest):
ollama run deepseek-r1:70b

۳- بعد این برنامه که رابط گرافیکی هست رو نصب کنید 
https://chatboxai.app
مدل رو بذارید روی OLLAMA
از اون پایین هم, چیزی که دانلود کردید رو انتخاب کنید. خودکار هرچی باشه رو نشون میده. بعد سیو کنید و تماااامم

![pic](https://pbs.twimg.com/media/GiNqXRsX0AERBob?format=jpg&name=small)


## MehdiAllahyari

خیلی راحت میتونید مدلهای جدید deepseek را دانلود و امتحان کنید. و خودتون ببینید که چقدر به کارتون میاد. توی ویدیوی زیر نشون دادم. 
 
من ۳ تا از مدلهای deepseek از جمله دوتا ورژن ۱.۵ میلیارد پارامتری و مدل ۷میلیاردی را امتحان کردم. چند تا سوال که بیشتر coding بودن پرسیدم و همگی خیلی بد جواب دادند. البته مدل ۷b خیلی بهتر بود ولی کد بازهم غلط بود. بعد همین سوالها را از Qwen ۱.۵ میلیاردی پرسیدم و عالی جواب داد. البته که چندتا سوال خیلی ارزیابی کاملی نیست ولی بازهم انتظارم خیلی بیشتر از اینها بود.
میخام بگم که درسته که این مدلهای deepseek خیلی سروصدا کرده ولی مدلهای کوچک که ازش distill شدن خیلی خوب کار نمیکنن بخصوص تو coding. اون مدلهای بزرگترش البته خیلی خوبند.  
نتیجه اخلاقی: خیلی به hype توجه نکنید. هر مدلی هم برای همه جور کاری خوب نیست. این مدلهای reasoning بدرد سوالهای ریاضی و اینجور مباحث میخورن. مثلا برای کدینگ خیلی مدلهای کوچکتر ولی به مراتب بهتر هست. پس خودتون را وابسته به یک مدل خاص نکنید.

https://x.com/MehdiAllahyari/status/1884087472939803011


## Qwen 2.5-Max

چت‌بات هوش‌مصنوعی Qwen 2.5-Max با پشتیبانی از زبان فارسی در دسترس عموم (نیاز به ثبت نام با ایمیل) قرار گرفت.

شرکت چینی علی‌بابا ادعا داره که این هوش‌مصنوعی حتی از DeepSeek هم قویتر و پیشرفته‌تر هست!

🌐لینک ورود به این چت‌بات:
https://chat.qwenlm.ai

![pic](https://pbs.twimg.com/media/Gih--r7XAAAon87?format=jpg&name=small)



## GPT Crawler 

Crawl a site to generate knowledge files to create your own custom GPT from one or multiple URLs

https://github.com/BuilderIO/gpt-crawler


## google

گوگل روزانه ۱ میلیون توکن رایگان برای استفاده از API های Gemini بهتون میده، توی مدل جدید 2.5 ولی به ۲۵ درخواست در روز محدود هست، میتونید واسه کارهای سنگین‌تر ازش استفاده کنید.
من نمیگم ولی بعضی‌ها با اکانت‌های مختلف چند تا کلید API باهاش میسازن.

![pic](https://pbs.twimg.com/media/GnwrM3dWYAAsEGD?format=png&name=small)


https://x.com/MrSoroushAhmadi/status/1908448978997223915