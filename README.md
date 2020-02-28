# BASE FIVEM CERTIFIEE CI-EVENTS 

Base simple contenant le nouvel extended en Weight, et les principaux ESX pour commencer un serveur sain sans erreurs, fonctionnels et surtout **plug and play**


# Fichiers 

Toutes les dépendances essentielmode et es_extended, le krz_menuperso, le policejob et toutes les dépendances, un shop avec le bahama, une armurerie, quelques jobs et quelques fonctions de véhicules, des portes et autres. Le double est prêt à recevoir **notre** double job avec extended en Weight

## Installation

Il y a quasi rien à faire, partez d'un serveur à zéro avec rien du tout dessus ni sur la base de donnée. Dans le cas échéant effacez tous les fichiers et toutes les entrées SQL.

Déposez le contenu du dossier **ressource** sur votre FTP ou serveur local.
Editez le server.cfg et modifiez :
### 1
endpoint_add_tcp "XXX.XXX.XXX:XXXXX"
endpoint_add_udp "XXX.XXX.XXX:XXXXX"

Mettre l'adresse IP du serveur et le port 

### 2
set mysql_connection_string "mysql://USER:PASS@IPBDD/BDDNAME?charset=utf8mb4_general_ci&supportBigNumbers=true&multipleStatements=true"

User : Nom d'utilisateur SQL
Pass : Password SQL
BDDName ; Nom de la base de donnée

### 3

Line 129 :
rcon_password "RCON"
RCON : RCON Password

Line 130 : 
sv_hostname "TEST ESX ONLY"
Change server name

Line 145 :
#add_principal identifier.steam:STEAMID group.admin # add the admin to the group
SteamId : ID Steam 

Line 151 & 153 :

sv_licenseKey LICENCEKEYMASTER

set steam_webApiKey  LICENCESTEAMAPI

Ajouter les licences keymaster et steam

### 4 
Ajoutez le SQL dans la base de donnée

### 5 
Reboot server and connect 

## Ajouts ESX

Sur notre Git, vous trouverez une grosse base de données de ESX divers et variés, tous ont étés testés et sont fonctionnel sur cette base ! Nous n'apportons aucuns support a ceux qui n'utilise pas cette base. 

## Video

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/dipgtsm6C-w/0.jpg)](https://www.youtube.com/watch?v=dipgtsm6C-w)

## Support

Discord : [https://discord.gg/pXrrH7R]

GitHub : https://github.com/orgs/CI-EVENTS/teams/fivem

Website : www.music2000.be


# BASE FIVEM CERTIFIED CI-EVENTS
Simple base containing the new extended Weight, and the main ESX to start a healthy server without errors, functional and above all **plug and play**.


# Files 

All the essentialmode and es_extended dependencies, the krz_menuperso, the policejob and all the dependencies, a shop with the bahama, an armoury, some jobs and some vehicle functions, doors and others. The double is ready to receive **our** double job with extended in Weight

## Installation

There's almost nothing to do, start from a zero server with nothing on it or on the database. If necessary delete all files and SQL entries.

Drop the contents of the folder **resource** on your FTP or local server.
Edit the server.cfg and modify :
### 1
endpoint_add_tcp "XXX.XXX.XXX:XXXXX"
endpoint_add_udp "XXX.XXX.XXX:XXXXX"

Set the server's IP address and port 

### 2
set mysql_connection_string "mysql://USER:PASS@IPBDD/BDDNAME?charset=utf8mb4_general_ci&supportBigNumbers=true&multipleStatements=true"

User: SQL username
Pass: SQL Password
DBName; Database name

### 3

Line 129:
rcon_password "RCON"
RCON: RCON Password

Line 130: 
sv_hostname "TEST ESX ONLY"
Change server name

Line 145:
#add_principal identifier.steam:STEAMID group.admin # add the admin to the group
SteamId: ID Steam 

Line 151 & 153:

sv_licenseKey LICENCEKEYMASTER

set steam_webApiKey LICENCESTEAMAPI

Add keymaster and steam licenses

### 4 
Add SQL to the database

### 5 
Reboot server and connect 

## ESX Additions

On our Git, you will find a large database of various ESX, all have been tested and are functional on this basis! We do not provide any support to those who do not use this database. 



## Support

Discord: [https://discord.gg/pXrrH7R]

GitHub: https://github.com/orgs/CI-EVENTS/teams/fivem

Website: www.music2000.be

Translated with www.DeepL.com/Translator (free version)
