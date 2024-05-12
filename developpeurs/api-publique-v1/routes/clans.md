# 🏢 Clans

Permet de récupérer les informations d'un clan.

<mark style="color:blue;">`GET`</mark> `https://api.rinaorc.com/clan/{clan.id}`

Récupérer les données d'un clan par ID.

#### Headers

| Name                                      | Type   | Description     |
| ----------------------------------------- | ------ | --------------- |
| API-Key<mark style="color:red;">\*</mark> | String | Clé API secrète |

{% tabs %}
{% tab title="404: Not Found " %}
```javascript
{
    "success": false,
    "message": "Clan not found"
}
```
{% endtab %}

{% tab title="200: OK " %}
```javascript
{
    "success": true,
    "clan": {
        "id": 973989203613634560,
        "name": "DreamTeam",
        "description": "&f&l#1 | Clan rinaorc !",
        "tag": null,
        "status": "INVITATIONS",
        "dailyExperience": 110800,
        "monthlyExperience": 224500,
        "totalExperience": 224500,
        "createdAt": 1652294721000,
        "players": [],
        "ranks": [],
        "games": []
    }
}
```
{% endtab %}
{% endtabs %}

<mark style="color:blue;">`GET`</mark> `https://api.rinaorc.com/clan/{clan.name}`

Récupérer les données d'un clan par nom.

{% tabs %}
{% tab title="404: Not Found " %}
```javascript
{
    "success": false,
    "message": "Clan not found"
}
```
{% endtab %}

{% tab title="200: OK " %}
```javascript
{
    "success": true,
    "clan": {
        "id": 973989203613634560,
        "name": "DreamTeam",
        "description": "&f&l#1 | Clan rinaorc !",
        "tag": null,
        "status": "INVITATIONS",
        "dailyExperience": 110800,
        "monthlyExperience": 224500,
        "totalExperience": 224500,
        "createdAt": 1652294721000,
        "players": [],
        "ranks": [],
        "games": []
    }
}
```
{% endtab %}
{% endtabs %}
