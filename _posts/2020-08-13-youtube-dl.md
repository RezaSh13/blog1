---
author: رضا شکری
type: image
featimg: youtube-dl.jpg
title: <div dir="rtl"> دانلود از یوتیوب با youtube-dl </div>
tags: [image]
category: [image]
---
<div dir="rtl"> 
برای دانلود از یوتیوب ابزار‌های مختلفی وجود داره مخصوصا تو گنو/لینوکس یه ابزار عالی به اسم youtube-dl وجود داره که می‌تونید به راحتی ازش استفاده کنید اما یه مشکلی که وجود داره به خاطر این که کامند لاین هست باید man دستور رو بخونید تا با آپشن‌های این ابزار آشنا بشید که داستان طولانی داره و کمتر کسی پیدا میشه man رو بخونه به خاطر یه دانلود ساده از یوتیوب به هر حال ترجیح دادم یه سرچی بزنم و یه کم هم با چیزی‌هایی که خودم بلدم تونستم دستور عجیب غریب زیر رو نوشتم که به این صورت کار می‌کنه:
</div>

<br> 
<div dir="rtl"> 

ساخت پوشه به اسم پلی‌ لیست
</div>

<br> 
<div dir="rtl"> 
شماره ویدیو براساس پلی لیست
</div>

<br> 
<div dir="rtl"> 

اسم ویدیو براساس پلی لیست
</div>

<br> 
<div dir="rtl"> 
دانلود تا زمانی ادامه پیدا می‌کنه که کامل شه اگه حین دانلود ارور بده یه وقفه 10 ثانیه اینجا میشه و دوباره شروع به دانلود می‌کنه
</div>

<br> 
<div dir="rtl"> 
نکته: اگه خودتون vpn دارید می‌تونید قسمت torify رو حذف کنید تا از سرویس تور برای دانلود استفاده نکنه.

</div>

<br> 


```yml
---
until torify youtube-dl --playlist-start 1  -o '%(playlist)s/%(playlist_index)s - %(title)s.%(ext)s' "https://www.youtube.com/playlist?list=PLbWvcwWtuDm06_VeGmZm9hocbNCYViKPL" ; do sleep 10 ; done ;
---
```

<br> 
<br> 


<div dir="rtl"> 

اگه سوالی داشتید تو ایشو گیت‌هاب بهم بگید بعدا قسمت کامنت رو فعال می‌کنم.
</div>
<br> 
https://github.com/rezash13/blog/issues

