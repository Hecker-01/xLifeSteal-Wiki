---
description: The commands xLifeSteal adds
---

# 🖥️ Commands

{% hint style="info" %}
<mark style="color:blue;">Blauwe tekst</mark> betekent dat dit deel aanpasbaar is in [config.yml](../../configuration/config.yml.md)

<mark style="color:yellow;">Gele tekst</mark> betekende dat dat deel aanpasbaar is in [messages.yml](../../configuration/messages.yml.md)
{% endhint %}

| Commando                                    | Permissie                               | Gebruik                                  | Beschrijving                                                                                                                  |
| ------------------------------------------- | --------------------------------------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [lifesteal](lifesteal.md)                   | `lifesteal.command.lifesteal`           | `/lifesteal`                             | Het hoofdcommando voor xLifeSteal geeft een <mark style="color:yellow;">help/info-bericht</mark> weer                         |
| [lifesteal ban](lifesteal.md#lifesteal-ban) | `lifesteal.command.lifesteal-ban`       | `/lifesteal ban <speler>`                | Verbant de opgegeven speler                                                                                                   |
| lifesteal unban                             | `lifesteal.command.lifesteal-unban`     | `/lifesteal unban <speler>`              | Heft de verbanning van de opgegeven speler op                                                                                 |
| lifesteal sethearts                         | `lifesteal.command.lifesteal-sethearts` | `/lifesteal sethearts <speler> <aantal>` | Stelt het aantal hartjes in dat een speler heeft.                                                                             |
| lifesteal reset                             | `lifesteal.command.lifesteal-reset`     | `/lifesteal reset <speler>`              | Zet een speler terug naar de <mark style="color:blue;">standaardhartjes</mark> en heft de verbanning op als hij verbannen was |
| [withdraw](withdraw.md)                     | `lifesteal.command.withdraw`            | `/withdraw [aantal]`                     | Trekt hartjes in. Als er geen aantal is gespecificeerd, wordt er 1 hartje ingetrokken                                         |
