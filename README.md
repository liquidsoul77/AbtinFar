#AbtinFar Calendar Component
#کامپوننت تقویم آبتین فار
Free of Charge Gift For Developers Published On Eid al-Ghadeer</br>
هدیه ای به مناسبت عید غدیر خم به برنامه نویسان  </br>
</br>
Abtin Graphical Farsi jalali,hijri,gregorian Caneldar , free of charge for .net win forms developrs</br>
 تقویم گرافیکی شمسی ، قمری ، میلادی ، بصورت رایگان برای برنامه نویسی بر پایه دات نت</br>
</br>
## AbtinFar

### Events :
### رخداد ها :

**bold**DateChanged**bold**
Returns Jalali Date Of Selected Date On AbtinFar Calendar</br>
بر اساس تاریخ انتخاب شده در تقویم آبتین فار ، تاریخ شمسی بر می گرداند</br>

**bold**DayEvents**bold**
Returns Day Event Of Selected Date On AbtinFar Calendar</br>
واقعه مربوط به تاریخ انتخاب شده در تقویم آبتین فار را بر می گرداند</br>

**bold**EnglishDateChanged**bold**
Returns Georgian Date Of Selected Date On AbtinFar Calendar</br>
بر اساس تاریخ انتخاب شده در تقویم آبتین فار ، تاریخ میلادی بر می گرداند</br>

**bold**ArabicDateChanged**bold**
Returns Hijri Date Of Selected Date On AbtinFar Calendar</br>
بر اساس تاریخ انتخاب شده در تقویم آبتین فار ، تاریخ قمری بر می گرداند</br>


### Properties :
### پراپرتی ها :

**bold**HijriAdjustment(Integer)**bold**
Hijri Date Small Change To Recieve Correct Date</br>
مقدار صحیح مثبت یا منفی ، جهت محاسبه تاریخ صحیح قمری</br>

**bold**CalendarStyle(string)**bold**
Blue : Blue Style</br> 
استایل آبی ,</br> 
Red : Ret Style</br> 
استایل قرمز ,</br> 
Green : Green Style</br>
استایل سبز</br>

**bold**HijriQamariDate(string)**bold**
Keeps Hijri Date (Cant Be Set)</br>
تاریخ قمری را در خود نگهمیدارد (نمی تواند مقداری بپذیرد)</br>

**bold**EnglishDate(Date)**bold**
Keeps Georgian Date and Can Be Set to Change Date of AbtinFar Calendar</br>
تاریخ میلادی را در خود نگهمیدارد ، با مقدار دهی آن تاریخ تقویم تغییر خواهد کرد</br>

**bold**CalendarDate(string)**bold**
Keeps Jalali Date and Can Be Set to Change Date of AbtinFar Calendar</br>
تاریخ شمسی را در خود نگهمیدارد ، با مقدار دهی آم تاریخ تقویم تغییر خواهد کرد</br>

**bold**PreviousCalendarDate(string)**bold**
Keeps Last Jalali Date</br>
تاریخ شمسی قبلی را در خود نگهمیدارد</br>


### Procedures :
### روال ها :

**bold**SetCalendarStyle**bold**
Set Calendar Style By Accepting string Parameter</br>
با قبول یک پارامتر متنی ، استایل تقویم را تغییر می دهد</br>

"Blue" : Blue Style</br> 
استایل آبی ,</br> 
"Red" : Ret Style </br>
استایل قرمز ,</br> 
"Green" : Green Style</br>
استایل سبز</br>

Example :</br>
مثال :</br>

```
SetCalendarStyle("Blue")
```
