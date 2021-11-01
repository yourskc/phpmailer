# phpmailer

It's helpful when you want to build a web site that send emails through your own gmail account.

The official site is
https://github.com/PHPMailer/PHPMailer

if fact, you don't need to clone the full source code from the repo, 
we just need one example named qmail.php 

	cd ~
	mkdir gmail_test
	cd gmail_test
	composer require phpmailer/phpmailer

download the examples\ folder from 

https://github.com/PHPMailer/PHPMailer

save to exmaples\ under gmail_test 

	cd examples
	cp gmail.phps gmail.php

modify the gmail account login information in gmail.php

	php gmail.php 

or, if you put everything in a folder under http web site,
you can test it from outside, for example, 

	sssss.xxx.net/gmail_test/gmail.php

then see if the the result is correct.

If you get some error message like "Please log in via your web browser and then try again" 
from google, please ref. to the followings to solve those issues

https://stackoverflow.com/questions/20337040/getting-error-while-sending-email-through-gmail-smtp-please-log-in-via-your-w

see the "9. Answer", 

1. allow less secure apps

https://support.google.com/accounts/answer/6010255

2. Unlock Captcha

https://accounts.google.com/b/0/DisplayUnlockCaptcha

Also, Google has list all the potential problems and fixes for us

https://support.google.com/mail/answer/7126229?visit_id=637713716244801072-1452480597&rd=1#cantsignin&zippy=%2C%E7%84%A1%E6%B3%95%E7%99%BB%E5%85%A5%E9%9B%BB%E5%AD%90%E9%83%B5%E4%BB%B6%E7%94%A8%E6%88%B6%E7%AB%AF