# timeworks-auto-emailer-v12
 Timeworks POS auto-emailer


## intallation
download and unzip the file "timework_auto_emailer_v12.7z" to your computer

before you run the .exe please ensure to setup SMTP email configuration 

## SMTP Email  configuration

1- Open the file  "./www/app/Config/email.php" and change the email SMTP email configuration


public $gmail = array(

	'host' => 'ssl://smtp.gmail.com',

	'port' => 465,
		
	'username' => 'mmm@gmail.com',
			
	'password' => 'mmm',

	'transport' => 'Smtp'
);

if you using gmail email address, make sure the email config have "less secure" enable


2- setting update the CC email address

make sure the cc email address is a valid address in order for the email to be carbon copied to solicitated email address

## IMPORTANT NOTE:
for "microsoft window embeded version" make sure to install the correctponding native client before running the auto-emailer exe


**contact leotoze@gmail.com for support**
