فردا اپدیت میشود.......

![R (2)](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/a064577c-9302-4f43-b3bf-3d4f84245a6f)
نام پروژه : ریورس تانل Chisel - برقرای تانل بین چندین سرور با ایپی 4 و ایپی 6 
---------------------------------------------------------------

-----------
**توضیح کوتاه در مورد این پروژه :**

- در این اسکریپت بوسیله ریورس تانل Chisel میخواهیم تانل را بین یک سرور و یا چندین سرور خارج و ایران، ایجاد کنیم.
- به طور مثال 3 سرور خارج دارید و بر روی هر کدام یک کانفیگ وایرگارد دارید، میتوانید آن ها را به یک سرور ایران وصل کنید و از یک سرور ایران برای 3 سرور خارجتان استفاده نمایید. این تانل ، توسط ریورس تانل انجام میشود.
- لطفا آموزش نوشتاری را با دقت بخوانید و با آزمون و خطا میتوانید تانل را با موفقیت ایجاد کنید.
- در این تانل پورت پیش فرضی استفاده نشده است ولی پیشنهاد میشه که پورت تانل 443 باشد.
- من در وقت آزاد این را درست کردم و ممکن است اشتباهاتی هم داخلش باشد. پیشاپیش ببخشید.
- خودم تمام روش ها را داخل سرور های مختلف تست کردم و جواب داده . بر روی دبیان 12 و اوبونتو 20 تست شده است.
- اگر از پنل v2ray استفاده میکنید و میخواهید با پرایوت ایپی، تانل را بسازید پس لطفا ایپی پرایوت ها را باز کنید.
- پنل شما در خارج باید نصب شده باشد
- مناسب برای وایرگارد و V2ray و Openvpn
- کانفیگ ریورس تانل با پرایوت ایپی به صورت خودکار میباشد.
- لطفا برای کانفیگ دوباره، نخست از منوی uninstall اقدام به حذف تانل کنید تا مشکلی پیش نیاید یا همان کانفیگ را دوباره کانفیگ کنید.
- پاک کردن و کانفیگ دوباره، حتی یک دقیقه از وقت گران بهای شما را نخواهد گرفت پس نیاز به ویرایش دستی نمی باشد.
- در آخر هر کانفیگ، ایپی 4 سرور ایران شما با پورت نهایی نمایش داده میشود که با استفاده از آن در کلاینت وایرگارد یا V2ray میتوانید به اینترنت متصل شوید. 

------------------------
![307981](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/39b2794b-fd04-4ae5-baea-d4b66138766e)
 **فهرست :**


 ----------------------

- **دسترسی سریع به اسکریپت** >> **[کلیک]()**
- **امکانات** >> **[کلیک]()**
- **آموزش** : 
- **تانل ** >> **[کلیک]()**
-  **تانل ** >> **[کلیک]()**
-  **تانل ** >> **[کلیک]()**
- **تانل ** >>  **[کلیک]()**
- **تانل **  >>  **[کلیک]()**
- **تانل **  >>  **[کلیک]()**
- **تانل **  >>  **[کلیک]()**
- **تانل **  >>  **[کلیک]()**
- **تانل  - TCP**  >>  **[کلیک]()**
- **تانل **  >>  **[کلیک]()**
     
     
     

------------------------
![check](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/13de8d36-dcfe-498b-9d99-440049c0cf14)
**امکانات**
-

- ریورس تانل بین تک سرور و یا چندین سرور خارج و ایران
- پشتیبانی از TCP و UDP
- قابلیت تانل بر روی تک پورت و چندین پورت 
- امکان تانل بر روی 5 سرور خارج و یک سرور ایران و برعکس
- مناسب برای V2ray و Openvpn و Wireguard
- استفاده از ایپی 4 و ایپی 6 و هم چنین پرایوت ایپی
- ساختن keygen به صورت اتوماتیک برای ریورس تانل
- قابلیت مشاهده جداگانه تمامی سرویس ها
- امکان حذف تمامی تانل ها و سرویس ها


 ------------------------------------------------------

![147-1472495_no-requirements-icon-vector-graphics-clipart](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/98d8c2bd-c9d2-4ecf-8db9-246b90e1ef0f)
 **پیش نیازها**

 - لطفا سرور اپدیت شده باشه.
 - میتوانید از اسکریپت اقای [Hwashemi](https://github.com/hawshemi/Linux-Optimizer) و یا [OPIRAN](https://github.com/opiran-club/VPS-Optimizer) هم برای بهینه سازی سرور در صورت تمایل استفاده نمایید. (پیش نیاز نیست)


----------------------------

  
  ![6348248](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/398f8b07-65be-472e-9821-631f7b70f783)
**آموزش**
-
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 4 - TCP - تک سرور**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel TCP [IPV4] >> IRAN**


 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/ac1ca7c7-3d36-4097-b57b-743c21badb32" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- کانفیگ سرور را با ایپی 4 و بر روی تک سرور میخواهیم انجام دهیم
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel TCP [IPV4] >> Kharej**


<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/d2aa0d7d-969f-41a2-bb79-bf5d0fc0373e" alt="Image" />
</p>

- میخواهیم سرور خارج را کانفیگ کنیم. کانفیگ تک سرور با ایپی 4 را در سرور ایران، انجام دادیم.
- در سرور خارج، من دو کانفیگ با پورت های 8080 و 8081 دارم پس تعداد کانفیگ را 2 قرار میدم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را 443 قرار میدم.
- پورت های کانفیگ خارج به ترتیب 8080 و 8081 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2ray استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
  

--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 4 - UDP - تک سرور**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel UDP [IPV4] << IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/180dd681-3852-4f85-82a5-851cb37a0e7c" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- کانفیگ سرور را با ایپی 4 و بر روی تک سرور میخواهیم انجام دهیم
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel UDP [IPV4] << Kharej**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/882d5be4-cfd6-4c52-a5fd-659a7eee77fc" alt="Image" />
</p>


- میخواهیم سرور خارج را کانفیگ کنیم. کانفیگ تک سرور با ایپی 4 را در سرور ایران، انجام دادیم.
- در سرور خارج، من یک کانفیگ وایرگارد با پورت 50824 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت وایرگارد استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
  


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 6 - TCP - تک سرور**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : **مسیر : Chisel TCP [IPV6] >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/b0926d15-fd7e-4871-8bf7-4e775f103f2c" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- کانفیگ سرور را با ایپی 6 و بر روی تک سرور میخواهیم انجام دهیم
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel TCP [IPV6] >> Kharej**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/4c2ac50e-1c9f-4486-9e0c-3d5d98cb9fab" alt="Image" />
</p>


- میخواهیم سرور خارج را کانفیگ کنیم. کانفیگ تک سرور با ایپی 6 را در سرور ایران، انجام دادیم.
- در سرور خارج، من یک کانفیگ با پورت 8080 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
- ایپی 6 سرور ایران را هم وارد میکنم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 8080 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayNG استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.

--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 6 - UDP - تک سرور**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : **مسیر : Chisel UDP [IPV6] >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/b0926d15-fd7e-4871-8bf7-4e775f103f2c" alt="Image" />
</p>



- نخست سرور ایران را کانفیگ میکنیم
- کانفیگ سرور را با ایپی 6 و بر روی تک سرور میخواهیم انجام دهیم
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel UDP [IPV6] >> Kharej**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/781010f2-aac6-472a-b19d-f9c37d29304a" alt="Image" />
</p>


- میخواهم سرور خارج را کانفیگ کنم. کانفیگ تک سرور با ایپی 6 را در سرور ایران، انجام دادیم.
- در سرور خارج، من یک کانفیگ وایرگارد با پورت 50824 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
- ایپی 6 سرور ایران را هم وارد میکنم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت وایرگارد استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
- خب کانفیگ های تک سرور را به پایان رساندیم. 

--------------------------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 4 - TCP - پنچ سرور خارج و یک سرور ایران**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel TCP [IPV4] [5] Kharej [1] IRAN >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/ICMP_tunnels/assets/119934376/a77e4553-49f9-4fe0-9bab-ae6e9f404d98" alt="Image" />
</p>


- من 2 سرور خارج و یک سرور ایران دارم و میخواهم از ایپی 4 و TCP استفاده کنم.
- نخست سرور ایران را کانفیگ میکنیم پس گزینه 6 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور را با ایپی 4 انجام میدهیم و میخواهیم دو سرور خارج به یک سرور ایران وصل بشوند.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : Chisel TCP [IPV4] [5] Kharej [1] IRAN >> Kharej 1**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/b8b39c96-d503-4ef0-98d5-daf83331b4bb" alt="Image" />
</p>


- میخواهم سرور اول خارج را کانفیگ کنم، پس گرینه اول را انتخاب میکنم.
-  در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 4 و TCP استفاده کنم.
- در سرور اول خارج ، من یک کانفیگ با پورت 8080 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 8080 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.


------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : Chisel TCP [IPV4] [5] Kharej [1] IRAN >> Kharej 2**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/b8b39c96-d503-4ef0-98d5-daf83331b4bb" alt="Image" />
</p>


- میخواهم سرور دوم خارج را کانفیگ کنم، پس گرینه دوم را انتخاب میکنم.
- در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 4 و TCP استفاده کنم.
- در سرور دوم خارج ، من یک کانفیگ با پورت 8083 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.سرور ایران یکسان است 
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 8083 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
- کانفیگ دو سرور خارج بر روی یک سرور ایران با ایپی 4 -TCP- انجام شد.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 4 - UDP - پنچ سرور خارج و یک سرور ایران**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel UDP [IPV4] [5] Kharej [1] IRAN >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/ICMP_tunnels/assets/119934376/a77e4553-49f9-4fe0-9bab-ae6e9f404d98" alt="Image" />
</p>


- من 2 سرور خارج و یک سرور ایران دارم و میخواهم از ایپی 4 و UDP استفاده کنم.
- نخست سرور ایران را کانفیگ میکنیم پس گزینه 6 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور را با ایپی 4 انجام میدهیم و میخواهیم دو سرور خارج به یک سرور ایران وصل بشوند.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : Chisel UDP [IPV4] [5] Kharej [1] IRAN >> Kharej 1**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/0d642f59-b109-43c2-aa37-0705e9ceafa4" alt="Image" />
</p>


- میخواهم سرور اول خارج را کانفیگ کنم، پس گرینه اول را انتخاب میکنم.
- در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 4 و UDP استفاده کنم.
- در سرور اول خارج ، من یک کانفیگ وایرگارد با پورت 50824 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت Wireguard استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.


------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : Chisel UDP [IPV4] [5] Kharej [1] IRAN >> Kharej 2**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/6d8be8aa-7a9f-4b59-b3c9-dba3e41c667d" alt="Image" />
</p>


- میخواهم سرور دوم خارج را کانفیگ کنم، پس گرینه دوم را انتخاب میکنم.
-  در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 4 و UDP استفاده کنم.
- در سرور دوم خارج ، من یک کانفیگ با پورت 50820 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.سرور ایران یکسان است 
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت Wireguard استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
- پس ما دو سرور خارج با دو کانفیگ جداگانه و با پورت های متفاوت را به یک سرور ایران وصل کردیم و میتوانیم از یک ایپی ایران برای دو کانفیگ وایرگارد، استفاده نماییم.
- کانفیگ دو سرور خارج بر روی یک سرور ایران با ایپی 4 -UDP- انجام شد.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 6 - TCP - پنچ سرور خارج و یک سرور ایران**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel TCP [IPV6] [5] Kharej [1] IRAN >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/3569b371-a1c8-4479-99c5-8f5c8bfa20ae" alt="Image" />
</p>


- من 2 سرور خارج و یک سرور ایران دارم و میخواهم از ایپی 6 و TCP استفاده کنم.
- نخست سرور ایران را کانفیگ میکنیم پس گزینه 6 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور را با ایپی 6 انجام میدهیم و میخواهیم دو سرور خارج به یک سرور ایران وصل بشوند.
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : Chisel TCP [IPV6] [5] Kharej [1] IRAN >> Kharej 1**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/ed96e5c0-bb84-4b95-971f-8ed36462809e" alt="Image" />
</p>


- میخواهم سرور اول خارج را کانفیگ کنم، پس گرینه اول را انتخاب میکنم.
-  در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 6 و TCP استفاده کنم.
- در سرور اول خارج ، من دو کانفیگ با پورت های 8080 و 8081 دارم پس تعداد کانفیگ را 2 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 و 6 سرور ایران را وارد میکنم. سرور ایران یکسان میباشد.
- پورت تانل را 443 قرار میدم.
- پورت های کانفیگ خارج من 8080 و 8081 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
- حالا باید سرور دوم خارج را کانفیگ کنیم.


----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : Chisel TCP [IPV6] [5] Kharej [1] IRAN >> Kharej 2**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/de956217-f901-4b37-88f5-f2cf86b23f74" alt="Image" />
</p>


- میخواهم سرور دوم خارج را کانفیگ کنم، پس گرینه دوم را انتخاب میکنم.
-  در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 6 و TCP استفاده کنم.
- در سرور دوم خارج ، من دو کانفیگ با پورت های  8083 و 8084 دارم پس تعداد کانفیگ را 2 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 و هم چنین 6 سرور ایران را وارد میکنم.سرور ایران یکسان است 
- پورت تانل را 443 قرار میدم.
- پورت های کانفیگ خارج من 8083 و 8084 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
- کانفیگ دو سرور خارج بر روی یک سرور ایران با ایپی 6 -TCP- انجام شد.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 6 - UDP - پنچ سرور خارج و یک سرور ایران**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel UDP [IPV6] [5] Kharej [1] IRAN >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/39e71594-fbe5-488b-abe4-6e8181427a35" alt="Image" />
</p>


- من 2 سرور خارج و یک سرور ایران دارم و میخواهم از ایپی 6 و UDP استفاده کنم.
- نخست سرور ایران را کانفیگ میکنیم پس گزینه 6 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور را با ایپی 6 انجام میدهیم و میخواهیم دو سرور خارج به یک سرور ایران وصل بشوند.
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج اول** 

**مسیر : Chisel UDP [IPV6] [5] Kharej [1] IRAN >> Kharej 1**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/caec4791-d4e0-4dd1-9aca-cfabcfbd9f55" alt="Image" />
</p>


- میخواهم سرور اول خارج را کانفیگ کنم، پس گرینه اول را انتخاب میکنم.
- در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 6 و UDP استفاده کنم.
- در سرور اول خارج ، من یک کانفیگ وایرگارد با پورت 50824 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 سرور ایران را وارد میکنم.
-  هم چنین ایپی 6 سرور ایران را وارد میکنم.
-  توجه نمایید سرور ایران یکسان میباشد.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت Wireguard استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.


------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج دوم** 

**مسیر : Chisel UDP [IPV4] [5] Kharej [1] IRAN >> Kharej 2**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/5fed26be-7569-411c-95e2-bd34dc3a7c82" alt="Image" />
</p>


- میخواهم سرور دوم خارج را کانفیگ کنم، پس گرینه دوم را انتخاب میکنم.
-  در این کانفیگ من 2 سرور خارج و 1 سرور ایران داشتم و میخواهم از ایپی 6 و UDP استفاده کنم.
- در سرور دوم خارج ، من یک کانفیگ با پورت 50820 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- ایپی 4 و 6 سرور ایران را وارد میکنم.سرور ایران یکسان است 
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت Wireguard استفاده نمایید.
- ایپی ایران شما به طور مثال در اینجا 91.91.91.91 میباشد.
- پس ما دو سرور خارج با دو کانفیگ جداگانه و با پورت های متفاوت را به یک سرور ایران وصل کردیم و میتوانیم از یک ایپی ایران برای دو کانفیگ وایرگارد، استفاده نماییم.
- کانفیگ دو سرور خارج بر روی یک سرور ایران با ایپی 6 -UDP- انجام شد.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 4 - TCP- پنچ سرور ایران و یک سرور خارج**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران اول**

**مسیر : Chisel TCP [IPV4] [5] IRAN [1] KHAREJ >> IRAN 1**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/6915720b-15d5-45ac-a2c2-c2f40fd92133" alt="Image" />
</p>


- من 2 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی 4 و TCP استفاده کنم.
- چون دو سرور ایران دارم پس تعداد سرور ایران را 2 انتخاب میکنم.
- نخست سرور اول ایران را کانفیگ میکنیم پس گزینه 1 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور اول را با ایپی 4 انجام میدهم و میخواهم 1 سرور خارج به دو سرور ایران وصل بشوند.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران دوم**

**مسیر : Chisel TCP [IPV4] [5] IRAN [1] KHAREJ >> IRAN 2**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/2e3f79c2-2bf2-43d0-8ac6-5c5e0c1cb1b5" alt="Image" />
</p>


- من 2 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی 4 و TCP استفاده کنم.
- سرور دوم ایران را کانفیگ میکنیم پس گزینه 2 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور دوم را با ایپی 4 انجام میدهم و میخواهم 1 سرور خارج به دو سرور ایران وصل بشوند.
- ایپی 4 سرور ایران را وارد میکنم. ایپی 4 سرور دوم ایران میباشد.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel TCP [IPV4] [5] IRAN [1] Kharej >> Kharej**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/c85df4bd-72fe-4c0d-ac70-3cf262e0b5d4" alt="Image" />
</p>


- میخواهم سرور خارج را کانفیگ کنم، پس گرینه 6 را انتخاب میکنم.
-  در این کانفیگ من 1 سرور خارج و 2 سرور ایران داشتم و میخواهم از ایپی 4 و TCP استفاده کنم.
- در سرور خارج ، من یک کانفیگ با پورت 8080 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- چون دو سرور ایران دارم باید دو بار کانفیگ را انجام دهم. به عبارتی ایپی 4 سرور اول ایران را وارد میکنم و کانفیگ را انجام میدهم و سپس ایپی سرور دوم ایران و کانفیگش را انجام میدهم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 8080 بود و برای هر دو سرور ایران 8080 خواهد بود. اگر پورت های بیشتری دارید تعداد بیشتری میتوانید وارد کنید.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی سرور اول ایران من 91.91.91.91 و ایپی سرور دوم ایران من 101.101.101.101 میباشد.
- از این طریق ما میتوانیم با دو ایپی ادرس سرور ایران به یک کانفیگ سرور خارج وصل بشویم و همزمان استفده کنیم.
- کانفیگ 1 سرور خارج بر روی دو سرور ایران با ایپی 4 -TCP- انجام شد.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 6 - TCP- پنچ سرور ایران و یک سرور خارج**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران اول**

**مسیر : Chisel TCP [IPV6] [5] IRAN [1] KHAREJ >> IRAN 1**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/93e90031-b3bb-43bb-bee5-9eeedec9793f" alt="Image" />
</p>


- من 2 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی 6 و TCP استفاده کنم.
- نخست سرور اول ایران را کانفیگ میکنیم پس گزینه 1 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور اول را با ایپی 6 انجام میدهم و میخواهم 1 سرور خارج به دو سرور ایران وصل بشوند.
- ایپی 6 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران دوم**

**مسیر : Chisel TCP [IPV6] [5] IRAN [1] KHAREJ >> IRAN 2**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/54ef5e26-4863-4a48-aabc-fd6a68b850ff" alt="Image" />
</p>


- من 2 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی 6 و TCP استفاده کنم.
- سرور دوم ایران را کانفیگ میکنیم پس گزینه 2 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور دوم را با ایپی 6 انجام میدهم و میخواهم 1 سرور خارج به دو سرور ایران وصل بشوند.
- ایپی 6 سرور ایران را وارد میکنم. ایپی 6 سرور دوم ایران میباشد.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel TCP [IPV6] [5] IRAN [1] Kharej >> Kharej**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/265ef4d1-5e1a-4827-8e0c-7589b33f4638" alt="Image" />
</p>


- میخواهم سرور خارج را کانفیگ کنم، پس گرینه 6 را انتخاب میکنم.
-  در این کانفیگ من 1 سرور خارج و 2 سرور ایران داشتم و میخواهم از ایپی 6 و TCP استفاده کنم.
- در سرور خارج ، من یک کانفیگ با پورت 8080 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- چون دو سرور ایران دارم باید دو بار کانفیگ را انجام دهم. به عبارتی ایپی 6 سرور اول ایران را وارد میکنم و کانفیگ را انجام میدهم و سپس ایپی سرور دوم ایران و کانفیگش را انجام میدهم.
- در کانفیگ سرور خارج با ایپی 6 : باید هم ایپی 4 و 6 سرور های ایران را به ترتیب بدهیم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 8080 بود و برای هر دو سرور ایران 8080 خواهد بود. اگر پورت های بیشتری دارید تعداد بیشتری میتوانید وارد کنید.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی سرور اول ایران من 91.91.91.91 و ایپی سرور دوم ایران من 101.101.101.101 میباشد.
- از این طریق ما میتوانیم با دو ایپی ادرس سرور ایران به یک کانفیگ سرور خارج وصل بشویم و همزمان استفده کنیم.
- کانفیگ 1 سرور خارج بر روی دو سرور ایران با ایپی 6 -TCP- انجام شد.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی 4 - UDP- پنچ سرور ایران و یک سرور خارج**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران اول**

**مسیر : Chisel UDP [IPV4] [5] IRAN [1] KHAREJ >> IRAN 1**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/3559dac2-f887-4f11-85c7-6d336e386e9f" alt="Image" />
</p>


- من 2 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی 4 و UDP استفاده کنم.
- چون دو سرور ایران دارم پس تعداد سرور ایران را 2 انتخاب میکنم.
- نخست سرور اول ایران را کانفیگ میکنیم پس گزینه 1 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور اول را با ایپی 4 انجام میدهم و میخواهم 1 سرور خارج به دو سرور ایران وصل بشوند.
- ایپی 4 سرور ایران را وارد میکنم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران دوم**

**مسیر : Chisel UDP [IPV4] [5] IRAN [1] KHAREJ >> IRAN 2**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/139c6822-769c-4ad1-8c29-c164bdbfcc9f" alt="Image" />
</p>


- من 2 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی 4 و UDP استفاده کنم.
- سرور دوم ایران را کانفیگ میکنیم پس گزینه 2 را انتخاب میکنم تا کانفیگ سرور ایران را آغاز کنم. 
- کانفیگ سرور دوم را با ایپی 4 انجام میدهم و میخواهم 1 سرور خارج به دو سرور ایران وصل بشوند.
- ایپی 4 سرور ایران را وارد میکنم. ایپی 4 سرور دوم ایران میباشد.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج** 

**مسیر : Chisel UDP [IPV4] [5] IRAN [1] Kharej >> Kharej**



<p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/56237f82-f0d4-4e13-8b72-112d83b1d987" alt="Image" />
</p>


- میخواهم سرور خارج را کانفیگ کنم، پس گرینه 6 را انتخاب میکنم.
-  در این کانفیگ من 1 سرور خارج و 2 سرور ایران داشتم و میخواهم از ایپی 4 و UDP استفاده کنم.
- در سرور خارج ، من یک کانفیگ وایرگارد با پورت 50824 دارم پس تعداد کانفیگ را 1 قرار میدهم.اگر تعداد پورت بیشتری دارید ، تعداد بیشتری انتخاب کنید.
- چون دو سرور ایران دارم باید دو بار کانفیگ را انجام دهم. به عبارتی ایپی 4 سرور اول ایران را وارد میکنم و کانفیگ را انجام میدهم و سپس ایپی سرور دوم ایران و کانفیگش را انجام میدهم.
- پورت تانل را 443 قرار میدم.
- پورت کانفیگ خارج من 50824 بود و برای هر دو سرور ایران 50824 خواهد بود. اگر پورت های بیشتری دارید تعداد بیشتری میتوانید وارد کنید.
- به طور مثال اگر دو پورت 50820 و 50824 دارید، برای هر سرور ایران به صورت جداگانه، پورت ها را قرار میدهیم.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت WIREGUAR استفاده نمایید.
- ایپی سرور اول ایران من 91.91.91.91 و ایپی سرور دوم ایران من 101.101.101.101 میباشد.
- از این طریق ما میتوانیم با دو ایپی ادرس سرور ایران به یک کانفیگ سرور خارج وصل بشویم و همزمان استفده کنیم. یعنی اگر دو کانفیگ وایرگارد دارید، هر دو کانفیگ با یک ایپی ایران کار خواهد کرد.
- کانفیگ 1 سرور خارج بر روی دو سرور ایران با ایپی 4 -UDP- انجام شد.
- برای کانفیگ ایپی 6 و UDP هم ماندد نمونه های قبلی، انجام دهید.


------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی پرایوت - TCP- تک سرور**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel TCP [Private IP] >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/862a74d4-32c4-4f59-b831-8d71cbe24392" alt="Image" />
</p>


- من 1 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی پرایوت و TCP استفاده کنم.
- نخست سرور ایران را کانفیگ میکنیم
- باید ایپی 4 سرور خارج و ایپی 4 سرور ایران را وارد نماییم.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج**

**مسیر : Chisel TCP [Private IP] >> KHAREJ**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/3af8308f-fbf0-4771-8369-747bfa4901df" alt="Image" />
</p>


- سرور ایران را کانفیگ کردیم و حالا سرور خارج را کانفیگ میکنیم.
- مانند سرور ایران، ایپی 4 سرور ایران و ایپی 4 سرور خارج را وارد میکنیم.
- من تنها یک کانفیگ با پورت 8080 در سرور خارج دارم، پس مقدار یک را برای تعداد کانفیگ، وارد میکنم.
- ایپی 4 ایران را دوباره وارد کنید ( این برای نمایش ایپی 4 ایران در آخر هر کانفیگ میباشد که ادرس و پورت پایانی شما، نمایش داده شود)
- پورت تانل را 443 قرار میدم.
- من یک کانفیگ با پورت 8080 در سرور خارج دارم پس برای پورت خارج ، 8080 را وارد میکنم.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت V2rayng استفاده نمایید.
- ایپی سرور اول ایران من 91.91.91.91 میباشد.
----------------------
![OIP2 (1)](https://github.com/Azumi67/V2ray_loadbalance_multipleServers/assets/119934376/3ec2f05f-3308-4441-8cce-62ab4776f4e2)
**ریورس تانل - ایپی پرایوت - UDP- تک سرور**
----------------------------------
![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور ایران**

**مسیر : Chisel UDP [Private IP] >> IRAN**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/374794b5-c111-4662-a11e-8b3a96144e5a" alt="Image" />
</p>


- من 1 سرور ایران و یک سرور خارج دارم و میخواهم از ایپی پرایوت و UDP استفاده کنم.
- نخست سرور ایران را کانفیگ میکنیم
- باید ایپی 4 سرور خارج و ایپی 4 سرور ایران را وارد نماییم اما من در کانفیگ TCP، اینکار را کرده بودم و فقط دوباره میخواهم بدون UNINSTALL، کانفیگ را دوباره انجام بدهم و برای همین نیازی نیست دوباره اینکار را انجام دهم و از این مرحله عبور میکند چون پرایوت ایپی هم اکنون در سرور من، قبلا کانفیگ شده است.
- پورت تانل را هم 443 قرار میدهم.
----------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/902a2efa-f48f-4048-bc2a-5be12143bef3) **سرور خارج**

**مسیر : Chisel UDP [Private IP] >> KHAREJ**



 <p align="right">
  <img src="https://github.com/Azumi67/Chisel_multipleServers/assets/119934376/305c0413-f529-4339-841f-56408134b53c" alt="Image" />
</p>


- سرور ایران را کانفیگ کردیم و حالا سرور خارج را کانفیگ میکنیم.
- مانند سرور ایران، ایپی 4 سرور ایران و ایپی 4 سرور خارج را وارد میکنیم ولی همانطور که گفتم ، چون قبلا کانفیگ کرده ایم، از این مرحله عبور خواهد کرد.
- من تنها یک کانفیگ وایرگارد با پورت 50824 در سرور خارج دارم، پس مقدار یک را برای تعداد کانفیگ، وارد میکنم.شما اگر تعداد پورت بیشتری دارید، تعداد بیشتری را وارد نمایید.
- ایپی 4 ایران را دوباره وارد کنید ( این برای نمایش ایپی 4 ایران در آخر هر کانفیگ میباشد که ادرس و پورت پایانی شما، نمایش داده شود)
- پورت تانل را 443 قرار میدم.
- من یک کانفیگ وایرگارد با پورت 50824 در سرور خارج دارم پس برای پورت خارج ، 50824 را وارد میکنم.
- در آخر، ایپی سرور ایرانتان با پورت مورد نظر را مشاهده میکنید. از این ادرس میتوانید در کلاینت WIREGUARD استفاده نمایید.
- ایپی سرور اول ایران من 91.91.91.91 میباشد.
----------------------
