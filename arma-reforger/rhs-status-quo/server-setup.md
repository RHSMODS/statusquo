# Server Setup

Firstly, please read the official Arma: Reforger documentation on setting up dedicated servers [here](https://community.bistudio.com/wiki/Arma\_Reforger:Server\_Hosting) and especially the section on [server configs](https://community.bistudio.com/wiki/Arma\_Reforger:Server\_Config).

In order to setup a dedicated server to use the RHS: Status Quo mod, you will need to edit your server configuration json file with the following settings:

Add the mod to the list of mods:

```json
"mods": [
            {
                "modId": "595F2BF2F44836FB",
                "name": "RHS: Status Quo"
            }
        ]
```

Or for the Dev version of the mod:

```json
"mods": [
            {
                "modId": "5CF4A61BE1D960C6",
                "name": "RHS: Status Quo Dev"
            }
        ]
```

To run one of the supplied scenarios you will need to also edit the following property:

```json
"scenarioId": "<Scenario ID>",
```

For example:

```json
"scenarioId": "{AAD43C10045857C1}Missions/RHS_Conflict.conf",
```

For a complete list of up-to-date scenario IDs please visit the Workshop scenario page and copy the ID as you see fit.

Stable: [https://reforger.armaplatform.com/workshop/595F2BF2F44836FB-RHS-StatusQuo/scenarios](https://reforger.armaplatform.com/workshop/595F2BF2F44836FB-RHS-StatusQuo/scenarios)

Dev: [https://reforger.armaplatform.com/workshop/5CF4A61BE1D960C6-RHS-StatusQuoDev/scenarios](https://reforger.armaplatform.com/workshop/5CF4A61BE1D960C6-RHS-StatusQuoDev/scenarios)
