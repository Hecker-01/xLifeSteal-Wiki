---
description: De commando's die xLifeSteal toevoegt
---

# 🖥️ Commando's

{% hint style="info" %}
<mark style="color:blue;">Blauwe tekst</mark> betekent dat dit onderdeel aanpasbaar is in [config.yml](../../configuration/config.yml.md)

<mark style="color:yellow;">Gele tekst</mark> betekende dat dit deel aanpasbaar is in [messages.yml](../../configuration/messages.yml.md)
{% endhint %}

| Command                                     | Permission                              | Usage                                    | Description                                                                                                                                                       |
| ------------------------------------------- | --------------------------------------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [lifesteal](lifesteal.md)                   | `lifesteal.command.lifesteal`           | `/lifesteal`                             | Het hoofdcommando voor xLifeSteal, geeft een <mark style="color:yellow;">help/info-bericht</mark> weer                                                            |
| [lifesteal ban](lifesteal.md#lifesteal-ban) | `lifesteal.command.lifesteal-ban`       | `/lifesteal ban <player>`                | Verbant de opgegeven speler                                                                                                                                       |
| lifesteal unban                             | `lifesteal.command.lifesteal-unban`     | `/lifesteal unban <player>`              | Heft de verbanning van de opgegeven speler op                                                                                                                     |
| lifesteal sethearts                         | `lifesteal.command.lifesteal-sethearts` | `/lifesteal sethearts <player> [amount]` | Stelt het aantal hartjes in dat een speler heeft. Als er geen aantal is opgegeven, wordt dit teruggezet naar de <mark style="color:blue;">standaardhartjes</mark> |
| lifesteal reset                             | `lifesteal.command.lifesteal-reset`     | `/lifesteal reset <player>`              | Zet een speler terug naar de <mark style="color:blue;">standaardhartjes</mark> en heft de verbanning op als hij verbannen was                                     |
| [withdraw](withdraw.md)                     | `lifesteal.command.withdraw`            | `/withdraw [amount]`                     | Trekt hartjes in. Als er geen bedrag is gespecificeerd, wordt er 1 hart ingetrokken                                                                               |
