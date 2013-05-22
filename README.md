#pttMailSender

pttMailSender is a web application to send PTT insite mail full-automatically.

#What It Do
1. login
2. choose receivers (yes, it support group mail!)
3. compose & send mail
4. logout 

#Getting Started
Simply pass these parameters:
```php
$myUser	  		string
$myPass	  		string
$mailSubject	string
$mailContent	string
```
config your mail list:
```php        
$ary_mailList array
```

#To-Do
* ANSI color parser
* user-friendly message
