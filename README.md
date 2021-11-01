[![Discord](https://img.shields.io/discord/868576710281531402.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/ftm8E4Avk7)  [![](https://poggit.pmmp.io/shield.api/Scoreboard)](https://poggit.pmmp.io/p/Scoreboard) [![](https://poggit.pmmp.io/shield.dl.total/Scoreboard)](https://poggit.pmmp.io/p/Scoreboard)

Our dear developer Ayzrix left us on October 18, 2021. To pay homage to him, I would like his best open source plugin to be updated. Please help me to keep it updated... Thanks in advance
# Scoreboard
###### A simple Pocketmine-MP plugin for creating optimized scoreboards.

## Command
| Name              | Usage             | Description                   | Enable                                    |
|-------------------|-------------------|-------------------------------|-------------------------------------------|
| Scoreboard        | /scoreboard       | Hide or show the scoreboard   | Put ``command`` on ``true`` in the [config](https://github.com/AyzrixYTB/Scoreboard/blob/main/resources/config.yml#L80) |

## Supported Tags
| Name                  | Tags                                                         | Download                                                                                                                                                                                           |
|-----------------------|---------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| Base                  | `{ping}`, `{tps}`, `{name}`, `{online}`, `{max_online}`, `{level}`, `{x}`, `{y}`, `{z}`, `{ip}`, `{port}`, `{uid}`, `{xuid}`, `{health}`, `{max_health}`, `{food}`, `{max_food}`, `{gamemode}`, `{scale}`, `{xplevel}`, `{id}`, `{damage}`, `{count}`, `{date}`   |                                                                           | |
| PiggyFactions         | `{faction_name}`, `{faction_rank}`, `{faction_power}`                                                 | [Download](https://poggit.pmmp.io/p/PiggyFactions)                                                                                                        |
| FactionsPro           | `{faction_name}`, `{faction_power}`                                                                   | [Download](https://poggit.pmmp.io/p/FactionsPro)                                                                                                          |   
| SimpleFaction         | `{faction_name}`, `{faction_rank}`, `{faction_power}`, `{faction_money}`                              | [Download](https://github.com/AyzrixYTB/SimpleFaction)                                                                                                    |
| EconomyAPI            | `{money}`                                                                                             | [Download](https://poggit.pmmp.io/p/EconomyAPI/)                                                                                                          |
| PurePerms             | `{rank}`, `{prefix}`, `{suffix}`                                                                      | [Download](https://poggit.pmmp.io/p/PurePerms)                                                                                                            |
| SkyBlock              | `{island_blocks}`, `{island_members}`, `{island_rank}`, `{island_size}`                               | [Download](https://poggit.pmmp.io/p/SkyBlock)                                                                                                             |
| SeeDevice             | `{device}`                                                                                            | [Download](https://github.com/Palente/SeeDevice)                                                                                                          |
| Bounty                | `{bounty}`                                                                                            | [Download](https://github.com/JaxkDev/Bounty)                                                                                                             |
| Prisons               | `{prisons_rank}`, `{prisons_prestige}`                                                                | [Download](https://github.com/TPEimperialPE/Prisons)                                                                                                      |
| OnlineTime            | `{onlinetime_session}`, `{onlinetime_total}`                                                          | [Download](https://github.com/Zedstar16/OnlineTime)                                                                                                       |
| CombatLogger          | `{combatlogger_time}`                                                                                 | [Download](https://github.com/JackNoordhuis/PocketMine-Plugins/tree/fcefe035e86150ddce59d7fda6f1bcdbf594a6e7/CombatLogger)                                |
| FightLogger           | `{fightlogger_time}`                                                                                  | [Download](https://poggit.pmmp.io/p/FightLogger)                                                                                                          |
| MyPlot                | `{myplot_owner}`, `{myplot_id}`                                                                       | [Download](https://poggit.pmmp.io/p/MyPlot)                                                                                                               |
| CoinsSystem           | `{coins}`                                                                                             | [Download](https://poggit.pmmp.io/p/CoinsSystem)                                                                                                          |
| KDR                   | `{kills}` `{deaths}` `{kdr}`                                                                          | [Download](https://poggit.pmmp.io/p/KDR)                                                                                                                  |
| Voteparty             | `{votes}` `{maxvotes}`                                                                                | [Download](https://poggit.pmmp.io/p/VoteParty)                                                                                                            |
| BankUI                | `{balance}`                                                                                           | [Download](https://poggit.pmmp.io/p/BankUI)                                                                                                               |
| RedSkyBlock           | `{island_members}` `{island_rank}` `{island_size}` `{island_value}` `{island_locked_status}`          | [Download](https://poggit.pmmp.io/p/RedSkyBlock)                                                                                                          |
| VanishV2              | `{vanish_fake_count}`                                                                                 | [Download](https://poggit.pmmp.io/p/VanishV2)                                                                                                             |
| MultiEconomy          | `{balance.currencyName}`                                                                              | [Download](https://poggit.pmmp.io/p/MultiEconomy)                                                                                                         |
| RankSystem            | `{rank}` `{prefix}`                                                                                   | [Download](https://poggit.pmmp.io/p/RankSystem)                                                                                                           |
| MultiServerCounter    | `{MultiServer.online}` `{MultiServer.Maxonline}`                                                      | [Download](https://poggit.pmmp.io/p/MultiServerCounter)                                                                                                   |
| Godmode               | `{god}`                                                                                               | [Download](https://poggit.pmmp.io/p/Godmode)                                                                                                              |
| FactionMaster         | `{faction_name}` `{faction_rank}` `{faction_power}` `{faction_level}` `{faction_xp}` `{faction_message}` `{faction_description}` `{faction_visibility}`    | [Download](https://poggit.pmmp.io/p/FactionMaster)                                                    |
## Config
```
#     _____                    _                         _
#    / ____|                  | |                       | |
#   | (___   ___ ___  _ __ ___| |__   ___   __ _ _ __ __| |
#    \___ \ / __/ _ \| '__/ _ \ '_ \ / _ \ / _` | '__/ _` |
#    ____) | (_| (_) | | |  __/ |_) | (_) | (_| | | | (_| |
#   |_____/ \___\___/|_|  \___|_.__/ \___/ \__,_|_|  \__,_|
#
#

# Time between a scoreboard update.
# RECOMMANDED: 2 seconds
update_time: 40 # TICKS 20 = 1 second

options:
  # {faction_name} {faction_rank} {faction_power}
  PiggyFactions: false
  # {faction_name} {faction_power}
  FactionsPro: false
  # {faction_name} {faction_rank} {faction_power} {faction_money}
  SimpleFaction: false
  # {money}
  EconomyAPI: false
  # {rank} {prefix} {suffix}
  PurePerms: false
  # {island_blocks} {island_members} {island_rank} {island_size}
  SkyBlock: false
  # {device}
  SeeDevice: false
  # {bounty}
  Bounty: false
  # {prisons_rank} {prisons_prestige}
  Prisons: false
  # {onlinetime_session} {onlinetime_total}
  OnlineTime: false
  # {combatlogger_time}
  CombatLogger: false
  # {fightlogger_time}
  FightLogger: false
  # {myplot_owner} {myplot_id}
  MyPlot: false
  # {coins}
  CoinsSystem: false
  # {kills} {deaths} {kdr}
  KDR: false
  # {votes} {maxvotes}
  VoteParty: false
  # {balance}
  BankUI: false
  # {island_members} {island_rank} {island_size} {island_value} {island_locked_status}
  RedSkyBlock: false
  # {vanish_fake_count}
  VanishV2: false
  # {balance.currencyName} -> Replace "currencyName" by the currency name
  MultiEconomy: false
  # {rank} {prefix}
  RankSystem: false
  # {MultiServer.online} {MultiServer.Maxonline}
  MultiServerCounter: false
  # {god}
  Godmode: false
  # {faction_name} {faction_rank} {faction_power} {faction_level} {faction_xp} {faction_message} {faction_description} {faction_visibility}
  FactionMaster: false

# BASE VARIABLES : {ping} {tps} {name} {online} {max_online} {level} {x} {y} {z} {ip} {port} {uid} {xuid} {health} {max_health} {food} {max_food} {gamemode} {scale} {date}

per_world: false
title: "§6Scoreboard"
lines:
    - "line1"
    - "line2"

# Edit just if per_world is on true
worlds:
  world:
    title: "§6Scoreboard"
    lines:
      - "line1"
      - "line2"

# true or false if you want the command for disable the scoreboard
command: false
command_description: "Hide or show the scoreboard"
command_success_hide: "§aYou have successfully hidden the scoreboard"
command_success_show: "§aYou have successfully displayed the scoreboard"

# Text for all the plugins using enable/disable functions (GodMode, Fly, and more)
enable: "§aEnable"
disable: "§cDisable"

# Put on true only if you have activated an Economy Support and if you want to convert the money text (Ex: 100000 = 100K 1000000 = 1M 1000000000 = 1B)
# Support : EconomyAPI, MultiEconomy, BankUI, CoinsSystem
convert_money: false

# Here, you can change the date format. All formats are available here https://www.php.net/manual/fr/datetime.format.php
date_format: "m/d/Y"
```
