# Baudrate Python3 WSL1

```bash
git clone https://github.com/hashy0917/baudrate-python3-wsl.git
cd python3-baudrate
pipenv install -r requirements.txt
pipenv run python3 baudrate.py -a
# pipenv run python3 baudrate.py -p /dev/ttyS(COM port number)

# or without pipenv
# pip install -r requirements.txt
# python3 baudrate.py -p /dev/ttyS(COM port number)
```
