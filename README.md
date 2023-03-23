# GLADIATOR SKRIPT V1.0

This is a skript for minecraft using the plugin skript.

## Getting Started

1. Install skript plugin on your minecraft server.
2. Open the scripts file
3. Add the gladiator.sk file there
4. Change the {prefix} variable change the XYZ location for the spectatinc are the spawn of the players.
5. Restart your minecraft server or use /skript reload gladiator.sk
6. Enjoy

### Commands

Starts the event and displays a message to the server
```
/gladiatorstart
```

Ends the event and displays a message to the server
```
/gladiatorstop
```

Starts a fight between two players
```
/startfight <player1> <player2>
```

For players to join the event
```
/event
```

To kick a player from the event
```
/eventkick
```

Shows the players that are in the event
```
/showplayers
```


### Permission

All the permisions

```
event.*
```

```
event.start
```

```
event.showplayers
```

```
event.kick
```

```
event.stop
```

```
event.startfight
```

"/event" is a command that anyone can run


## Requierd plugins

* [Essentials](https://github.com/SkriptLang/Skript/releases) - 1.19^
* [Skript](https://essentialsx.net/downloads.html?branch=stable) - 1.19^


## Authors

* **StXfTb** - *Initial work* - [StXfTb](https://github.com/StXf1b)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
