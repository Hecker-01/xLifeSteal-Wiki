---
description: The commands xLifeSteal adds
---

# 🖥️ Commands

{% hint style="info" %}
<mark style="color:blue;">Blue text</mark> means that that part is customizable in [config.yml](../../configuration/config.yml.md)

<mark style="color:yellow;">Yellow text</mark> meant that that part is customizable in [messages.yml](../../configuration/messages.yml.md)
{% endhint %}

| Command                                                 | Permission                              | Usage                                    | Description                                                                                                                  |
| ------------------------------------------------------- | --------------------------------------- | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| [lifesteal](lifesteal.md)                               | `lifesteal.command.lifesteal`           | `/lifesteal`                             | The main command for xLifeSteal, displays a <mark style="color:yellow;">help/info message</mark>                             |
| [lifesteal ban](lifesteal.md#lifesteal-ban)             | `lifesteal.command.lifesteal-ban`       | `/lifesteal ban <player>`                | Ban the specified player                                                                                                     |
| [lifesteal unban](lifesteal.md#lifesteal-unban)         | `lifesteal.command.lifesteal-unban`     | `/lifesteal unban <player>`              | Unbans the specified player                                                                                                  |
| [lifesteal sethearts](lifesteal.md#lifesteal-sethearts) | `lifesteal.command.lifesteal-sethearts` | `/lifesteal sethearts <player> [amount]` | Sets the amount of hearts a player has if no amount specified, it will reset to the <mark style="color:blue;">default</mark> |
| [lifesteal reset](lifesteal.md#lifesteal-reset)         | `lifesteal.command.lifesteal-reset`     | `/lifesteal reset <player>`              | Resets a player to the default hearts and unbans them if they were banned                                                    |
| [withdraw](withdraw.md)                                 | `lifesteal.command.withdraw`            | `/withdraw [amount]`                     | Withdraws hearts, if no amount specified it will withdraw 1 heart                                                            |
