# SC_Pin_recovery
Smart card pin recovery

```
usage: SC_Pin_Recovery.py [-h] [--startpin STARTPIN] [--lenght LENGHT] [--wait WAIT] [--reset RESET]

SmartCard Pin recovery tool

optional arguments:
  -h, --help           show this help message and exit
  --startpin STARTPIN  Pin to be cracked.
  --lenght LENGHT      Lenght of the Pin to be cracked.
  --wait WAIT          Wait in seconds
  --reset RESET        Reset the chip after try
```

Conect your card reader and insert a simm card then fire it:
```
python3 SIMM_Pin_Recovery.py --startpin 0 --lenght 7
```
