# Cops_FiveM
[![GitHub release](https://img.shields.io/github/release/FiveM-Scripts/Cops_FiveM.svg)](https://github.com/FiveM-Scripts/Cops_FiveM/releases/latest) [![GitHub license](https://img.shields.io/github/license/FiveM-Scripts/Cops_FiveM.svg)](https://github.com/FiveM-Scripts/Cops_FiveM/blob/master/LICENSE)

Cops_FiveM is a resource mainly for RP servers. It gives servers a cops system with loadouts, vehicles, fines, ...    
You can find a complete overview with all the features [here](docs/features.md).

## Changelog
You can find the changelog [here](CHANGELOG.md).

## Community Support
A Discord server is available: [![](https://discordapp.com/api/guilds/361144123681538060/widget.png)](https://discord.gg/qnAqCEd)

## Requirements
- [Mysql](https://dev.mysql.com/downloads/mysql/)
- [ghmattimysql](https://github.com/GHMatti/ghmattimysql)

## Installation
1. Verify that you have installed the requirements from above.
2. Download the latest version from the [GitHub repository](https://github.com/FiveM-Scripts/Cops_FiveM/releases/latest).    
3. Only copy the subdirectory *police* to the *resources* folder on your server.    
4. Edit [config file](https://github.com/FiveM-Scripts/Cops_FiveM/blob/master/police/config/config.lua) to your preferences.    
5. Add *start police* in your server.cfg (make sure you start this resource after all dependencies).
6. The first time when you enter the game you will need to add yourself to the police database.    
you can do this in your server console enter `CopAddAdmin 1` or `CopAdd 1` press **enter** and you should receive a confirmation message.

## Commands
You can use these commands with RCON (`CopAdd` / `CopAddAdmin` / `CopDept`/ `CopRem` / `CopRank`).    
To see how to use them, just type the command you want without any parameter.

## Departments
| ID | Name |
| -- | ---- |
| 0  | Park Rangers |
| 1  | Los Santos Police Department|
| 2  | Sheriff's Department |
| 3  | State Highway Patrol |
| 4  | Prison Department|

## Ranks
| ID | Name |
| -- | ---- |
| 0  | Trainee|
| 1  | Trooper|
| 2  | Master Police Officer|
| 3  | Sergeant|
| 4  | Lieutenant|
| 5  | Captain|
| 6  | Chief of Police|
| 7  | Admin Police Rank|

## Contribute
If you are a developer and would like to contribute any help is welcome!.   
The contribution guide can be found [here](https://github.com/Kyominii/Cops_FiveM/blob/master/CONTRIBUTING.md).

## Supported Scripts
you can find some supported scripts [here](docs/scripts.md).