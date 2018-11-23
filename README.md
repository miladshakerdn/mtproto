<div dir="rtl">

حتما برای شما هم پیش آمده که قصد راه اندازی یک MtProto برای تلگرام را داشته باشید و از پکیج های فراوانی استفاده کرده باشید .

اکثر پکیج ها دارای مشکل در نصب , کندی شدید سرعت هنگام اتصال به سرور و یا دارای آموزش بسیار سخت و غیر اصولی نیز می باشد . 

اما همگی را به فراموشی بسپارید ...

در این پست , پکیجی را برای هر سه سیستم عامل معروف Centos , Debian و Ubuntu آماده ساخته ام که فقط کافیست با اجرای یک کد کوتاه , تمامی مراحل را به سادگی پشت سر بگذارید و فقط در عرض چند ثانیه لینک اتصال به MtProto رو برای تلگرام دریافت نماید و از آن لذت ببرید .

موارد مورد نیاز: داشتن یک VPS و یا سرور اختصاصی لینوکس در خارج از ایران و داشتن یک  دسترسی SSH به VPS یا سرور اختصاصی .

<h1>آموزش نصب MTProto پروکسی سرور</h1>

1- توسط SSH به سرور خودتون متصل شوید.
2- سپس بر اساس نوع سیستم عامل خود دستورات صحیح زیر را انتخاب کرده و وارد کرده تا مراحل نصب بصورت اتوماتیک آغاز گردد.

<h2>
برای سیستم عامل های Ubuntu و Debian
</h2>

<pre dir="ltr">apt-get install -y curl && curl -O https://raw.githubusercontent.com/vahidmajidi/mtproto/master/Mtproto-Ubuntu-Debian.sh && bash MTProto-NodeJs-FastSetup-UD.sh</pre>

<h2>برای سیستم عامل Centos</h2>

<pre dir="ltr">yum install wget -y && wget -N --no-check-certificate https://raw.githubusercontent.com/vahidmajidi/mtproto/master/Mtproto-Centos.sh && bash MTProto-NodeJs-FastSetup-CentOS.sh</pre>

<h2>پاک کردن همه فایل ها و سرویس نصب شده از سرور برای نصب و راه اندازی مجدد</h2>

<pre dir="ltr">wget -N --no-check-certificate https://raw.githubusercontent.com/vahidmajidi/mtproto/master/Mtproto-Uninstall.sh && bash UnInstall.sh</pre>

- در آغاز فرآیند پورت انتخابی شما را می خواهد و در صورت اینکه پورتی وارد نکنید بصورت پیشفرض پورتی تعیین میگردد.
پس از انجام مرحله بالا در انتهای مسیر اطلاعات سرور و همچنین لینک های اتصال به پروکسی تلگرام را برای شما به نمایش در میاورد.

</div>
