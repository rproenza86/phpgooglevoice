A php based class of Google Voice API to send sms.

Update:
05/28/2010: update to version 0.2, update google login auth.

Usage:
```
require 'class.googlevoice.php';
$gv = new GoogleVoice("GmailAccount", "GmailPassword");
$gv->sms("PhoneNumber", "TextMsg");
echo $gv->status;
```