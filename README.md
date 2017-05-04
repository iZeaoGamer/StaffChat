# StaffChat
[<img src="https://img.shields.io/badge/Poggit-view-brightgreen.svg" width="100" height="25" />](https://poggit.pmmp.io/ci/ThunderDoesPlugins/StaffChat/StaffChat)

Private Staff Chat Channel Plugin

Allows you to create staff chat

commands:

| Command             | popurse                                                  |
|---------------------|----------------------------------------------------------|
| say                 | send a message to staff channel                          |
| on/off/toggle       | switch current chat mode(chats directly into staff chat) |
| reload              | reloads configs and flushes internal data                |
| attach <true/false> | Attach console into/out of staff chat                    |

Configs:

| Config Value | Usage                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------|
| prefix       | Used to send a message directly into staff chat Example: ".hello staff" you may set it to any value you prefer |
| auto-attach  | Automatically make console listen to staff chat on start?                                                      |
| format       | Staff chat formmating example: "![bold]StaffChat![reset]%sender%>%msg%"                                        |

There's also refrences inside config file
