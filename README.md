# mnist
<font face="vazir" size=3>
داده آموزشی مسئله دارای ۶۰۰۰۰ سطر و ۷۸۵ ستون است.
    <br>
   هر سطر اطلاعات یک عکس را نشان می‌دهد. اولین ستون نشان‌دهنده برچسب نمونه (عددی داخل عکس) و ۷۸۴ ستونی که در ادامه آمده‌اند، ویژگی‌های یک عکس هستند.
    <br>
       عکس را می‌توان یک ماتریس در نظر گرفت که هر درایه آن یک پیکسل است. عدد موجود در هر درایه بین ۰ و ۲۵۵ است و هر چه به ۲۵۵ نزدیک شود، درجه روشنایی آن پیکسل بیشتر خواهد بود. بنابراین پیکسلی با عدد ۲۵۵ کامل سفید و پیکسلی با عدد ۰ کامل سیاه نمایش داده خواهد شد. مثلا در عکس بالا، پیکسل‌هایی که درون عدد ۴ هستند، عدد بزرگتری نسبت به حاشیه تصویر که سیاه رنگ است، دارند.
    <br>
    دیتاست این تمرین نیز در حقیقت شامل ۶۰ هزار ماتریس ۲۸*۲۸ است. برای راحتی شما هر کدام از ماتریس‌های ۲۸*۲۸ را هموار کرده‌ایم. به این معنی که سطرهای ماتریس را در امتداد همدیگر چیده و یک آرایه ۷۸۴تایی درست کرده‌ایم.
    <br>
    برای همین است که هر سطر دیتافریم (هر عکس) دارای ۷۸۴ ستون یا ویژگی است و یک برچسب هم دارد.
    <br>
    نامگذاری ستون‌های دیتافریم به صورت $i*j$ است. یعنی عددی که در این ستون مشاهده می‌کنید در ماتریس اصلی (قبل از هموار شدن) در سطر $i$ ام و ستون $j$ ام قرار داشته.
    <br>
    ستون دیگری به اسم <code>label</code> فقط در دیتافریم آموزش یافت می‌شود که نشانگر عدد درون تصویر است.
</font>
