# PEP BeautifulSoup4 parsing

The parser collects data about all PEPs, check statuses and extract them to a *.csv file, collects information about Python version status and downloads *.zip archives.

## 1. Project Techs

- Python
- BeautifulSoup4
- Prettytable
- Logging

## 2. How to launch

```
git clone https://github.com/zakharovvladimir/bs4_parser_pep.git
```
```
cd bs4_parser_pep
```
```
python3 -m venv venv
```
```
source env/bin/activate
```
```
python3 -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```

## 3. Commands

Create *.csv with statuses and amounts
```
python main.py pep -o file
```
Prettytable with: "Ссылка на документацию", "Версия", "Статус"
```
python main.py latest-versions -o pretty 
```
Links about Python updates
```
python main.py whats-new
```

## 4. Author

Vladimir Zakharov // 
vladimir.zakharov.s@yandex.ru

## 5. License
[MIT](https://choosealicense.com/licenses/mit/)
