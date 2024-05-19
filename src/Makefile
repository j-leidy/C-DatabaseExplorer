output: Db_Functions.o Helpers.o Menus.o Printers.o Sqlite3_Db_Explorer.o sqlite3.o
	echo Building...
	g++ Db_Functions.o Helpers.o Menus.o Printers.o Sqlite3_Db_Explorer.o sqlite3.o -o output -lsqlite3

Db_Functions.o: Db_Functions.cpp 
	g++ -c Db_Functions.cpp

Helpers.o: Helpers.cpp
	echo Compiling Helpers.cpp...
	g++ -c Helpers.cpp

Menus.o: Menus.cpp
	echo Compiling Menus.cpp... 
	g++ -c Menus.cpp

Printers.o: Printers.cpp
	echo Compiling Printers.cpp... 
	g++ -c Printers.cpp

Sqlite3_Db_Explorer.o: Sqlite3_Db_Explorer.cpp
	echo Compiling Sqlite3_Db_Explorer.cpp...
	g++ -c Sqlite3_Db_Explorer.cpp

sqlite3.o: sqlite_resources/sqlite3.c sqlite_resources/sqlite3.h
	echo Compiling sqlite3...
	gcc -c sqlite_resources/sqlite3.c

