# GSMpinRecovery
GSM pin recovery

```
usage: GSMpinRecovery.py [-h] [--startpin STARTPIN] [--lenght LENGHT] [--wait WAIT] [--reset RESET]

GSM Pin recovery tool

optional arguments:
  -h, --help           show this help message and exit
  --startpin STARTPIN  Pin to be cracked.
  --lenght LENGHT      Lenght of the Pin to be cracked.
  --wait WAIT          Wait in seconds
  --reset RESET        Reset the chip after try
```

Conect your card reader and insert a gsm sim card then fire it:
```
python3 GSMpinRecovery.py --startpin 0 --lenght 7
```
