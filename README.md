# Os9

1)

chown : مالکیت فایل به کاربر را تغییر میدهیم

chown -h : برای تغییر مالکیت سمبولیک لینک ها استفاده می شود

chown -c : اگر که تغییراتی صورت گرفته باشد آنهارا نشان میدهد 

chown -f : یرای کاهش خطاها


gpasswd: با کمک این دستور می توان گروههای خوددرسیستم عامل لینوکس مدیریت کرد

gpasswd-M : کاربر جدید اضافه میکند

gpasswd-r : رمز گروه را پاک میکنه

gpasswd-d : حذف کاربر از گروه

2)

id -u -n : نمایش نام کاربری

id mojtaba : نمایش اطلاعات خواسته شده برای یوزر با آیدی mojtaba


3)

--> sudo useradd oslab
--> sudo passwd oslab


4)

--> sudo groupadd sadjad
--> sudo groupadd Uni
--> sudo usermod -G sadjad
--> sudo usermod -G Uni
--> sudo gpasswd -A oslab sadjad


5)
--> sudo useradd os2
--> sudo gpasswd -a os2 sajjad
--> sudo userdel os2
