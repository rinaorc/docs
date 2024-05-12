# 👪 Joueurs

Permet de récupérer les données liées à un joueur.

<mark style="color:blue;">`GET`</mark> `https://api.rinaorc.com/player/{player.uuid}`

Permet de récupérer les données liées à un joueur.

#### Headers

| Name                                      | Type   | Description     |
| ----------------------------------------- | ------ | --------------- |
| API-Key<mark style="color:red;">\*</mark> | String | Clé API secrète |

{% tabs %}
{% tab title="200: OK " %}
```javascript
{
    "success": true,
    "player": {
        "uuid": "ceaa096a-64f6-4433-a727-f61264610a60",
        "name": "adrien2431",
        "displayName": "§c[Lead.Dev] §cadrien2431",
        "colorName": "§cadrien2431",
        "rank": {
            "id": 101,
            "name": "Lead.Dev",
            "color": "§c",
            "chatPrefix": "[Lead.Dev] ",
            "tabPrefix": "[Lead.Dev] "
        },
        "isOnline": false,
        "connectionMethod": "PREMIUM",
        "firstLogin": 1510799453000,
        "lastLogin": 1652367198883,
        "totalPlayedTime": 40858301655,
        "monthlyPlayedTime": 536488356,
        "links": {
            "discord": "154275543838228481"
        },
        "hasBoost": true,
        "hasBoostUntil": 1652370680449,
        "boostMonths": 27,
        "aura": 20560,
        "aliases": [
            "adrien2431old",
            "adrien2431_old"
        ],
        "friends": null,
        "leveling": {
            "level": 8,
            "experience": 525,
            "requiredExperience": 2975,
            "monthlyExperience": 4050,
            "power": 320
        },
        "clan": {
            "id": 973989203613634560,
            "name": "DreamTeam",
            "description": "&f&l#1 | Clan rinaorc !",
            "tag": null,
            "status": "INVITATIONS",
            "dailyExperience": 93900,
            "monthlyExperience": 207600,
            "totalExperience": 207600,
            "createdAt": 1652294721000
        },
        "skin": {
            "texture": "ewogICJ0aW1lc3RhbXAiIDogMTY0ODkzMjEwOTE1OCwKICAicHJvZmlsZUlkIiA6ICJmZTYxY2RiMjUyMTA0ODYzYTljY2E2ODAwZDRiMzgzZSIsCiAgInByb2ZpbGVOYW1lIiA6ICJNeVNoYWRvd3MiLAogICJzaWduYXR1cmVSZXF1aXJlZCIgOiB0cnVlLAogICJ0ZXh0dXJlcyIgOiB7CiAgICAiU0tJTiIgOiB7CiAgICAgICJ1cmwiIDogImh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZjlkMGFhYmJkZTYyZDQ4NDYzY2RmOGZjMzkyY2Q5MzJmMjM5YWUzN2Q5MTk5ZDE2NzAwM2UyZjZjODc5ZTczNyIKICAgIH0KICB9Cn0=",
            "signature": "CT2LeAmfCinmjnNmDpwW2miC/msmXudzA7x7dBwAB+/8U5t5ZNOFk6levD/h/hE5xClFeDixijrWK6HDD8triwGi1EjRhWc9ov79+uzi5T/VVG2183zqb+Ubx0KwpfF+nt+pVeWiA8mvc5AlPOUgIYaeStaXLkz3B+c6buiwQmEMhIb/p2zecOiTz2tw/f7tR8fvBRGdD7tKk6FUlSNfPQuAzu9WztPSN9QYCAdItcGws76y+17L5Q2URxmxrnwU/R00V2uCBBrwnHJ+kEWR0aJRoPIjOSBF532egIQ3+sU5zXwR385qVapW7BeYOkOtWOovaxm1n7uARZA3uzbuO2a0GRt5toVDzk2rGJS1AN8qNtPKuPRLEICPaycxFWbtMvmGx3N5T4jQ/GEFxvKmB72qvy/dL4hdBEBk9PmNbiPyxNJWR+e4EGrh4T6l3NdMfOUH3O+/p8aQh6HutOZP1fMfAb++3JGodPP3ZoAlSPMEgrPIn8c4TnxDjYY6v47jkXbmUFgl1eNIUszBM06or5FKk3NM8oqv+AFLYiiKSem2y0RlAS7/LTc/mnopdZEYHC0Ja5Fk4bw5UaAyeBWocfGGjb2OufZmXhxgQjAO/h7SF8TBG/Hi3XX0/k7GQvlAbhbBUQAt1w+abaGWRp11W9HhWXRdnqM+ro1zsKeMXu8=",
            "updateType": "MANUAL",
            "lastUpdated": 1648939309000
        },
        "games": {},
        "stats": {}
    }
}
```
{% endtab %}

{% tab title="404: Not Found Player not found" %}
```javascript
{
    "success": false,
    "message": "Player not found"
}
```
{% endtab %}
{% endtabs %}

<mark style="color:blue;">`GET`</mark> `https://api.rinaorc.com/player/{player.name}`

Permet de récupérer les données liées à un joueur.

#### Headers

| Name                                      | Type   | Description     |
| ----------------------------------------- | ------ | --------------- |
| API-Key<mark style="color:red;">\*</mark> | String | Clé API secrète |

{% tabs %}
{% tab title="200: OK " %}
```javascript
{
    "success": true,
    "player": {
        "uuid": "ceaa096a-64f6-4433-a727-f61264610a60",
        "name": "adrien2431",
        "displayName": "§c[Lead.Dev] §cadrien2431",
        "colorName": "§cadrien2431",
        "rank": {
            "id": 101,
            "name": "Lead.Dev",
            "color": "§c",
            "chatPrefix": "[Lead.Dev] ",
            "tabPrefix": "[Lead.Dev] "
        },
        "isOnline": false,
        "connectionMethod": "PREMIUM",
        "firstLogin": 1510799453000,
        "lastLogin": 1652367198883,
        "totalPlayedTime": 40858301655,
        "monthlyPlayedTime": 536488356,
        "links": {
            "discord": "154275543838228481"
        },
        "hasBoost": true,
        "hasBoostUntil": 1652370680449,
        "boostMonths": 27,
        "aura": 20560,
        "aliases": [
            "adrien2431old",
            "adrien2431_old"
        ],
        "friends": null,
        "leveling": {
            "level": 8,
            "experience": 525,
            "requiredExperience": 2975,
            "monthlyExperience": 4050,
            "power": 320
        },
        "clan": {
            "id": 973989203613634560,
            "name": "DreamTeam",
            "description": "&f&l#1 | Clan rinaorc !",
            "tag": null,
            "status": "INVITATIONS",
            "dailyExperience": 93900,
            "monthlyExperience": 207600,
            "totalExperience": 207600,
            "createdAt": 1652294721000
        },
        "skin": {
            "texture": "ewogICJ0aW1lc3RhbXAiIDogMTY0ODkzMjEwOTE1OCwKICAicHJvZmlsZUlkIiA6ICJmZTYxY2RiMjUyMTA0ODYzYTljY2E2ODAwZDRiMzgzZSIsCiAgInByb2ZpbGVOYW1lIiA6ICJNeVNoYWRvd3MiLAogICJzaWduYXR1cmVSZXF1aXJlZCIgOiB0cnVlLAogICJ0ZXh0dXJlcyIgOiB7CiAgICAiU0tJTiIgOiB7CiAgICAgICJ1cmwiIDogImh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZjlkMGFhYmJkZTYyZDQ4NDYzY2RmOGZjMzkyY2Q5MzJmMjM5YWUzN2Q5MTk5ZDE2NzAwM2UyZjZjODc5ZTczNyIKICAgIH0KICB9Cn0=",
            "signature": "CT2LeAmfCinmjnNmDpwW2miC/msmXudzA7x7dBwAB+/8U5t5ZNOFk6levD/h/hE5xClFeDixijrWK6HDD8triwGi1EjRhWc9ov79+uzi5T/VVG2183zqb+Ubx0KwpfF+nt+pVeWiA8mvc5AlPOUgIYaeStaXLkz3B+c6buiwQmEMhIb/p2zecOiTz2tw/f7tR8fvBRGdD7tKk6FUlSNfPQuAzu9WztPSN9QYCAdItcGws76y+17L5Q2URxmxrnwU/R00V2uCBBrwnHJ+kEWR0aJRoPIjOSBF532egIQ3+sU5zXwR385qVapW7BeYOkOtWOovaxm1n7uARZA3uzbuO2a0GRt5toVDzk2rGJS1AN8qNtPKuPRLEICPaycxFWbtMvmGx3N5T4jQ/GEFxvKmB72qvy/dL4hdBEBk9PmNbiPyxNJWR+e4EGrh4T6l3NdMfOUH3O+/p8aQh6HutOZP1fMfAb++3JGodPP3ZoAlSPMEgrPIn8c4TnxDjYY6v47jkXbmUFgl1eNIUszBM06or5FKk3NM8oqv+AFLYiiKSem2y0RlAS7/LTc/mnopdZEYHC0Ja5Fk4bw5UaAyeBWocfGGjb2OufZmXhxgQjAO/h7SF8TBG/Hi3XX0/k7GQvlAbhbBUQAt1w+abaGWRp11W9HhWXRdnqM+ro1zsKeMXu8=",
            "updateType": "MANUAL",
            "lastUpdated": 1648939309000
        },
        "games": {},
        "stats": {}
    }
}
```
{% endtab %}

{% tab title="404: Not Found " %}
```javascript
{
    "success": false,
    "message": "Player not found"
}
```
{% endtab %}
{% endtabs %}
