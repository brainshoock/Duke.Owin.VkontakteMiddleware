VkontakteMiddleware
===================

mvc 5 owin module for vk.com (vkontakte.ru)

News
-------------
Updated to version 1.3 - fixed problem with autorization on vk.com

How to use?
-------------
1) Add nuget package - search for "Duke.Owin.VkontakteMiddleware"
2) Add module in Startup.Auth.cs of your mvc 5 project

app.UseVkontakteAuthentication("{AppId}", "{AppSecret}", "{PERMISSIONS}");

{PERMISSIONS} - it is the comma-separated string. For example "email,audio"
More info here http://vk.com/dev/permissions

How to register app in vk.com?
-------------
Info here http://vk.com/dev

Live examples 
-------------
 http://freelistenonline.com/

 http://m.freelistenonline.com/

Updated to v1.2 
-------------
Now it correctly return scope "Email" for Owin 2.1.0.0

Contacts
-------------
skype - duke_nuken23


 
