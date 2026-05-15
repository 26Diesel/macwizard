
# Mac wizard

Lightweight script to automate mac address obfuscation using MacChanger



## Usage
Change the address of the defautl network interface (wlan0):
```bash
python3 macwizard.py
```
Promt a menu to select the desired network interface:
```bash
python3 macwizard.py -p
```
## Options

| Argument | Effect                                |
|----------|---------------------------------------|
| -h       | Show the help page                    |
| -p       | Prompt the network interface selector |
| -i       | Specify the network interface         |
| -c       | Show current configuration            |

## Examples
Change mac address of wlan0
```bash
python3 macwizard.py -i wlan0
```
Prompt the network interface selector
```bash
python3 macwizard.py -p
```


They fear what they can't trace. Knowledge is freedom.
