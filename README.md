# Iran-national-divisions
اطلاعات موجود در این دیتابیس داخل 6 جدول موجود میباشد که بدلیل استفاده های مختلف و پلن های توسعه در این 6 جدول گنجانده شده است
<br>
ترتیب خوانش جداول<br>
statediv_countries<br>
جدول اسامی کشورها که در اینجا فقط یک رکورد موجود است که ایران میباشد<br>
statediv_province<br>
جدول لیست استان ها که با country_code به جدول لیست کشورها متصل است و شامل 31 رکورد میباشد<br>
statediv_cities<br>
جدول لیست شهرستان ها که با  state_code به استان مربوطه متصل است و شامل 457 رکورد میباشد<br>
statediv_sections<br>
جدول لیست بخش ها که بوسیله province_id به استان ها و city_id به شهرستان ها متصل است و شامل 1125 رکورد میباشد<br>
statediv_district<br>
جدول لیست دهستان ها که بوسیله province_id به استان ها و city_id به شهرستان ها و state_id به بخش ها متصل است و شامل 2674 رکورد میباشد<br>
statediv_place<br>
جدول لیست اماکن که با province_id به استان ها و city_id به شهرستان ها و state_id به بخش ها و district_id به دهستان ها  متصل میباشد<br>
<br>
شیوه خوانش کد شناسه آماری<br>
مثال: منزل آباد<br>
![Screenshot 2025-01-04 223952](https://github.com/user-attachments/assets/ddc42ec4-733c-4b87-bb82-b470e28f4b28)<br>
کدشناسه آماری<br>
0916050002166247<br>
رکورد در جدول statediv_place برابر است با 49245 <br>
province_id = 09<br>
city_id = 16<br>
state_id = 05<br>
district_id = 0002<br>
block_code = 166247تقسیمات کشوری ایران بر اساس سایت اداره آمار بصورت اسکریپت دیتابیس<br>
