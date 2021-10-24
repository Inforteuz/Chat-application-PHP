Chat Xizmati

##

### O`rnatish

* Men Xammp serveridan foydalanishni yaxshi ko'raman, shuning uchun Xammp serverini o'rnatishni taklif qilaman. O'rnatilgandan so'ng, quyidagi ko'rsatmalarni bajaring.

* Xammp serverini ishga tushiring: undov :.

* Ushbu ilovani :open_file_folder: c://xammp/www/chat_application ichiga joylaganingizga ishonch hosil qiling.

* Tarmoq tepsisidagi wamp belgisiga sichqonchaning chap tugmasi bosiladi, u yerda variantlar ro'yxati ko'rsatiladi "Hamma xizmatlarni ishga tushirish" -ni tanlang.

* Keyin kerakli brauzerni oching va manzil satriga localhost kiriting Enter tugmasini bosing: undov: u xammp serverining standart sahifasini ko'rsatadi.


##

Chat application (ENGLISH VERSION)


##

### Installation

* I like to use Wamp server, so I suggest installing Wamp server . Once that is installed, execute the following               instructions.

* Run wamp server :exclamation:.

* Make sure you have placed this entire application inside  :open_file_folder: c://wamp/www/chat_application.

* Left click on the wamp icon in system tray  It will display list of options Select “start all services”.

* Then open your preffered browser and type localhost in address bar Hit enter :exclamation:  It will show the default page     of wamp server.


##
Endi bu index.php (mening PHP fayl nomim) ni url oxiriga qo'shing.

#### Ma'lumotlar bazasini o'rnatish (.SQL fayli dbase papkasida mavjud)

#### 1-usul: MySQL orqali chat_info faylini IMPORT qilish
#### 2-usul: Mysql konsolidan foydalanish!
Men mysql -dan foydalanishni yaxshi ko'raman, shuning uchun men mysql -ni o'rnatishni taklif qilaman. O'rnatilgandan so'ng, quyidagi buyruqlarni bajaring, havotir olmang, u Wamp serverida o'rnatilgan!

* Agar siz wamp ishlatayotgan bo'lsangiz, buni sinab ko'rishingiz mumkin. Oldin your_Database_name ni ishlating.

* Wamp server belgisini bosing, keyin MYSQL> MSQL Console -ni qidiring va ishga tushiring.

* Agar sizda parol bo'lmasa, Enter ni bosing va yozing:

* mysql> database_name -dan foydalaning;

* mysql> faylingizning manba joylashuvi;

* Agar sizda parol bo'lsa, siz parolni kiritishingizni so'raysiz. Avval parolingizni kiriting, keyin yozing:

* mysql> database_name -dan foydalaning;

* mysql> faylingizning manba joylashuvi;

##

#### 2 -usul: qalam2:

* Tizim tepsisidagi wamp belgisini chap tugmasini bosing va PHPMyAdmin -ni ishga tushiring (PHPMyAdmin orqali ma'lumotlar bazasiga kiring).

* Fayllarni import qilish yorlig'iga o'ting

* "Browse" tugmasini bosing, kompyuteringizda SQL faylini toping (u sql ma'lumotlar bazasi papkasida mavjud), "Ochish" tugmasini bosing va "O'tish" tugmasini bosing.


##

### Hissa qo'shish

1. ** _ commit yarating ** **: `git checkout -b my-new-feature` qiling

2. **_Commit_** ga o'zgartirishlaringizni kiriting: `git commit -m 'Ba'zi xususiyat qo'shing''

3. **_Push_** ga: `git push origin my-new-feature` qiling va hissangizni qo`shing

4. ** Qabul qilish so'rovini yuboring **

5. ** _ Mazza qilib foydalaning! _ **

##

#### Chatning ko`rinishiga Misol
![alt tag](https://github.com/Inforte18/Chat-application-PHP/blob/main/Pictures/Chat.png)

##

### E`tiboringiz uchun rahmat!

Now include this index.php (my php file name) at the end of the url.

#### Setting Up The Database (.SQL File is present in dbase Folder)

#### Method 1 :pencil2: Using Mysql Console !

I like to use mysql, so I suggest installing mysql. Once that is installed, execute the following commands don't worry it is inbuilt in Wamp server !.

* If you are using wamp you can try this. Just type use your_Database_name first.

* Click your wamp server icon then look for MYSQL > MSQL Console then run it.

* If you dont have password, just hit enter and type :

* mysql> use database_name;

* mysql> source location_of_your_file;

* If you have password, you will promt to enter a password. Enter you password first then type:

* mysql> use database_name;

* mysql> source location_of_your_file;

##

#### Method 2 :pencil2: 

* Left click on the wamp icon in system tray and run PHPMyAdmin (Access your database via PHPMyAdmin).

* Go to the Import files tab

* Click Browse, locate the SQL file on your computer (it is present in sql database folder), click Open, and then click Go.


##

### Contributing

1. Create your **_branch_**: `git checkout -b my-new-feature`

2. **_Commit_** your changes: `git commit -m 'Add some feature'`

3. **_Push_** to the branch: `git push origin my-new-feature`

4. Send a **Pull Request**

5. **_Enjoy!_**

##

#### Example

![alt tag](https://github.com/Inforte18/Chat-application-PHP/blob/main/Pictures/Chat.png)

##
