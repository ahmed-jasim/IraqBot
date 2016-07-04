البوت العراقي

# التنصيب
قم بانشاء سيرفر على سبيل اذا كنت لا تعرف سيرفر قم 
بانشائه هنا www.c9.io

قم بفتح ترمنال وظع الاوامر ادناه
```sh
# الامر الاول.
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
```
ثم اظغط انتر
```
# باقي الاوامرظع كل سطر بمفرده.
cd $HOME
git clone https://github.com/ahmed-jasim/IraqBot.git -b supergroups
cd IraqBot
chmod +x launch.sh
./launch.sh install
./launch.sh
# هنا سوف يطلب منك رقم الهاتف .
# بعد وضع رقم الهاتف سوف يطلب منك رمز يصلك الى تلكرام قم بوضعه.
```


* * *

### Realm configuration

الان قم بلدخول الى البوت وارسل 
/id
سوف تحصل على الايدي الخاص بك قم بلانتقال الى ملفات البوت
افتح /data/config.lua    وظع الايدي فيه كمال في المثال اسفلهه
```
  sudo_users = {
    196458060,
    164118057,
    4957018,
    0,
    YourID
  }
```

### راسلوني للاستفسار:

للاستفسار : [@help4_bot](http://telegram.me/help4_bot)


# لا تخجل في طرح اسئلتكم : 

قناتنا
[@world_net](http://telegram.me/world_net)


