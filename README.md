# Programs-For-Temp-Directory

---

## About programs:

There are two programs - main (temp cleaner) and additional for tests (file creator).
The main program is supposed to clean TEMP directory on your computer. Usually, it's C:\Users\{User}\Appdata\Local\Temp (User - your username in system).
The additional program is used for creating files in TEMP directory for some tests (e.g. deleting these files using the main program).

---

## About project structure:

- archive (7z) (directory): contains an archive and file `hash_sums.txt` with archive hash sums (`IMPORTANT`: archive does not contain it`s directory, so if you check hash sums, check hash sums of this archive);
- exe (directory): contains executable programs;
- icons (directory): contains icons for programs;
- temp_cleaner.py (file): main file - cleans TEMP directory;
- file_creator.py (file): additional file - creates file in TEMP directory.

#### `P.S.` 
You can use one of next commands in CMD to see directory for temporary files on your computer: `echo %TEMP%` or `echo %TMP%`.
Also you can choose an easier way and write `temp` after using the next combination: `Win + R`.