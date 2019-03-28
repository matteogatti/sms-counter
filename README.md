SMS Counter
=============================

Character counter for SMS messages.

Usage
----------

```javascript
SmsCounter.count('content of the SMS')
```

This will return the following object:

```javascript
{
	encoding: "GSM_7BIT",
	length: 18,
	messages: 1,
	per_message: 160,
	remaining: 142
}
```

Thanks to
----
https://github.com/danxexe/sms-counter
