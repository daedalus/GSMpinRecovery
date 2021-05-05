# GSMpinRecovery
GSM pin recovery

__WARNING__: _This tool may block your GSM SIM card and if you dont have your PUK annotated you will not be able to unblock it._


```
usage: GSMpinRecovery.py [-h] [--startpin STARTPIN] [--lenght LENGHT] [--wait WAIT] [--reset RESET] [--rcpt RCPT] [--sender SENDER]

GSM Pin recovery tool

optional arguments:
  -h, --help           show this help message and exit
  --startpin STARTPIN  Pin to be cracked.
  --lenght LENGHT      Lenght of the Pin to be cracked.
  --wait WAIT          Wait in seconds
  --reset RESET        Reset the chip after n tries
  --rcpt RCPT          Recipient of email
  --sender SENDER      Sender of the email
```

Conect your card reader and insert a gsm sim card then fire it:
```
python3 GSMpinRecovery.py --startpin 0 --lenght 7
```

Optionaly we can set a recipient email and a sender for notification on successful recovery:
```
python3 GSMpinRecovery.py --startpin 439990 --lenght 8 --rcpt notifyme@example.com --sender noreply@example.com
```
