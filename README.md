# KPL scanner notes: 
## VSCode Debugger setup: 
1. Must open this project as root directory.
2. Muse compile this project in Debug mode.
```
gcc -g .\scanner.c .\reader.c .\charcode.c .\token.c .\error.c -o dm-scanner.exe
```
3. Configure 'launch.json' to debug specific program.
4. Use GDB.
