# “The Past, Present, and Future of Local Storage for Web Applications”

for the original content visit

**http://diveinto.html5doctor.com/storage.html**

sometimes you'll need to store data on the client side to keep track of prefences or run time state, nowdays these files can be stored in the registery in formats like INI files , or XML files, or you can invent your own format, but before HTML5 brwosers didn't have this option and had to rely on cookies, butg coockies had downsides like slowing down your web application, or sending unencrypted data over the internet and they are limited to 4 KB in size, and we wanted these issues solved,
so Microsoft invented userData which allowed the the storage of up to 64 KB of data per domain, and with trusted domains storing up to 10 times more that space using XML files 

In 2002 adobe introduced a feature in Flash 6 called Flash coockies that allows flash enviroment to store 100 KB of data later they developed a Flash to JavaScript bridge called AMASS which stands for (AJAX Massive Storage System) and was limited due to Flash's design quircks and by 2006 the creation of ExternalInterface in Flash 8 came to life which is alot faster and easier, then they re-wrote AMASS and integrated it into the Dojo Toolkit that gives each domain 100 KB for free 

in 2007 google waged in with Gears which is an open source plug-in and by prompting the user once, Gears can store unlimited amounts of data per domain in SQL database tabels

all that is pre-HTMl5 era, now we have what's called Local Storage or DOM Storage, and they are implemented in the browsers so this means it is always avilable, 

to use these data you need create it by name and retrieve it by the same key, the name is a key and the data can be anything supported by Java script like boolean, strings, integers, and so on, and to keep track of these data types you need to embed it in a trap called The Storage Event and this storage event is suppurted everywhere the Local Storage object is suppported 

Neverthless there are still 5 MB storage limitation and some browsers like Opera allow the user to limit the each site's storage space

for the future 5 MB might see a litlle less than we require as web developers, so there's a new API has been standarised across all browsers platforms and devices called WEB SQL Database which gives you the freedom to select, update, insert and delete from within your Javascript code 

thank you for reading,