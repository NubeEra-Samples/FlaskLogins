## Functionality We cover

Register, Login Dashboard and logout

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required dependencies

##### Windows:
```zsh
pip install -r requirements.txt 
```

##### macOS/Linux:
```zsh
pip3 install -r requirements.txt
```

## Usage

##### Windows:
```zsh
python app.py
```
##### macOS/Linux:
```zsh
python3 app.py
```


## Database

##### Install Sqlite3:
```zsh
1. download 
https://www.sqlite.org/2022/sqlite-tools-win32-x86-3390300.zip

2. extract to this folder
c:\sqlite3
```

##### Setting Path(Local/System):
```zsh
set path=%path%;c:\sqlite3;
```

##### Open Sqlite3:
```zsh
sqlite3 database.db
```

##### Execute SQL Commands:
```zsh
Display All Tables

sqlite>.tables

sqlite>select * from user;



```