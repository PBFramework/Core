# Core
Runs on PB v10.5 and above

PBCore Objects
1. appservice.pbl
2. appsystem.pbl
3. fscsvc.pbl
4. santilmo.pbl
5. PBCoreSys.pbl

DBObjects
Database run's on MSSQL.  
1. Restore Database <MAINAPP>.
2. Create <fconnect> Users
	* userID : fconnect
	* PW : fconnect
	* Grand Server Role to fconnect<serveradmin>
	* Grant Database Role to fconnect<group_Connect>
3. Create <mainappusers> Users
	* userID : mainappusers
	* PW : maldito
	* Grant Database Role to mainappusers<group_MainAPP>	
	* Grand Server Role to mainappusers<serveradmin>
	* You can also find mainappusers parameters in FLOGIN table for any posible changes

Enjoy...
