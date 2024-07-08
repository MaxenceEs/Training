# Python virtual environments
To create a virtual environment :
`python -m venv venv`

To create a file with list of installed packages and their version :
`pip freeze > requirements.txt`

To install all dependencies from a `requirements` file :
`pip install -r requirements.txt`


# SQLite
To install SQLite :
* Download [sqlite-tools-win-x64-version.zip package](https://www.sqlite.org/download.html)
* Unzip it. It should contains 3 files :
    * sqldiff.exe
    * sqlite3.exe
    * sqlite3_analyzer.exe
* Add the unzipped folder path to the environment variable `path` (ie : `sqlite-tools-win-x64-version`)  

To check if it well installed, run the cmd command `sqlite3`.  
It should display the following message :
```
C:\>sqlite3
SQLite version 3.46.0 2024-05-23 13:25:27 (UTF-16 console I/O)
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite>
```