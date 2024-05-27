# ⛓️ Prisons

Permet de récupérer les données du mode de jeu Prison Odyssey liées à un joueur.

<mark style="color:blue;">`GET`</mark> `https://api.rinaorc.com/prison/{player.uuid / player.name}`

#### Headers

| Name                                      | Type   | Description     |
| ----------------------------------------- | ------ | --------------- |
| API-Key<mark style="color:red;">\*</mark> | String | Clé API secrète |

{% tabs %}
{% tab title="200: OK " %}
```javascript
{
	"success": true,
	"level": 2500,
	"rank": "COSMIQUE",
	"pass": {
		"premium": true,
		"totalExperience": 587500
	},
	"activeRobots": {
		"ONE": {
			"id": 1227568470538915840,
			"type": "TOKENS",
			"rarity": "NORMAL",
			"level": 2,
			"affixes": [
				{
					"stat": "TOKENS_MULTIPLIER",
					"tier": 1,
					"roll": 0.2,
					"greater": false
				}
			]
		}
	},
	"unlockedWarps": [],
	"boosters": [],
	"unlockedKits": [],
	"lastUsedKits": {
		"ULTIME": 1713632143007,
		"FONDA": 1712741179218,
		"VOYAGEUR": 1712741183518,
		"FONDA_1": 1712778971856,
		"FONDA_2": 1715160860699
	},
	"unlockedTitles": [],
	"scanner": {
		"tier": "TIER_4"
	},
	"autoTrash": {
		"enabled": true,
		"rarity": "COMMON"
	},
	"passClaimed": [
		"TIER_1",
		"TIER_1P",
		"TIER_2P",
		"TIER_2",
		"TIER_3",
		"TIER_3P"
	],
	"quests": [
		{
			"quest": "TIME_II",
			"startedAt": 1712741174575,
			"data": 360000,
			"finishedAt": 1714377703738
		},
		{
			"quest": "MINE_III",
			"startedAt": 1712741175822,
			"data": 109056
		},
		{
			"quest": "MINE_II",
			"startedAt": 1716758489662,
			"data": 0
		},
		{
			"quest": "RECYCLE_I",
			"startedAt": 1716758489662,
			"data": 0
		},
		{
			"quest": "PICKAXE_I",
			"startedAt": 1716758489662,
			"data": 0
		},
		{
			"quest": "BLACKSMITH_I",
			"startedAt": 1716758489662,
			"data": 0
		},
		{
			"quest": "PVP_I",
			"startedAt": 1716758489662,
			"data": 0
		},
		{
			"quest": "SCANNER_I",
			"startedAt": 1716758489662,
			"data": 0
		},
		{
			"quest": "TIME_I",
			"startedAt": 1716810253921,
			"data": 3600,
			"finishedAt": 1716826445001
		}
	],
	"settings": {},
	"lastClaimAfk": 1715512215849,
	"resetsRecords2": {},
	"minePlanetForced": "PLANET_161",
	"pets": {
		"PIGEON": {
			"id": 1233526875598426112,
			"type": "PIGEON",
			"totalExperience": 135000,
			"age": 0
		},
		"MOUSTIQUE": {
			"id": 1233526875602620416,
			"type": "MOUSTIQUE",
			"totalExperience": 105000,
			"age": 0
		},
		"PIG": {
			"id": 1233526875606814721,
			"type": "PIG",
			"totalExperience": 30000,
			"age": 0
		},
		"FROG": {
			"id": 1233526875611009028,
			"type": "FROG",
			"totalExperience": 25000,
			"age": 0
		},
		"MOUSE": {
			"id": 1234116843886678016,
			"type": "MOUSE",
			"totalExperience": 75000,
			"age": 0
		},
		"OWL_RAINBOW": {
			"id": 1238431917390311424,
			"type": "OWL_RAINBOW",
			"totalExperience": 0,
			"age": 0
		}
	},
	"petsSlots": {},
	"pickaxe": {
		"prestige": 3,
		"level": 72,
		"experience": 481034,
		"rarity": "COMMON",
		"blocksMined": 4508337135,
		"blocksRawMined": 109056,
		"blocksRawMinedSinceEvolution": 483,
		"crafter": "adrien2431",
		"destroyable": false,
		"sacrifiedLevels": 1090,
		"enchants": {
			"FORTUNE": 1406,
			"EFFICIENCY": 100,
			"TOKENS": 55,
			"VEINMINER": 79,
			"NUKE": 1000,
			"FRACTURE": 250,
			"EXPLOSION": 250,
			"STATS": 1,
			"XP": 295,
			"JACKHAMMER": 32
		},
		"disabledEnchants": [
			"ASTRE_CELESTE",
			"NUKE",
			"NUEE",
			"ASTRO_FLAME",
			"VEINMINER"
		],
		"lockedEnchants": [],
		"gems": {
			"ONE": {
				"type": "RUBIS",
				"rarity": "COMMON",
				"maxDurability": 8,
				"durability": 8,
				"affixes": [
					{
						"stat": "RINACOINS_MULTIPLIER",
						"tier": 1,
						"roll": 0.2,
						"greater": false
					},
					{
						"stat": "PICKAXE_XP_MULTIPLIER",
						"tier": 1,
						"roll": 0.8,
						"greater": false
					}
				]
			}
		},
		"affixes": [
			{
				"stat": "RINACOINS_MULTIPLIER",
				"tier": 1,
				"roll": 1.8,
				"greater": false
			},
			{
				"stat": "TOKENS_MULTIPLIER",
				"tier": 1,
				"roll": 1.5,
				"greater": false
			}
		]
	},
	"backpack": {
		"content": {},
		"enchants": {
			"BP_AUTO_SELL": 1329708,
			"BP_SIZE": 309186
		},
		"disabledEnchants": [
			"BP_AUTO_SELL"
		],
		"lockedEnchants": [],
		"gems": {},
		"affixes": []
	},
	"mineSettings": {
		"state": "CLOSE",
		"taxe": 5.0,
		"maxPlayers": 4,
		"bans": []
	},
	"artefacts": {},
	"maxLevelsBonus": {},
	"keys": {},
	"currencies": [
		{
			"name": "RINACOINS",
			"amount": 5579989055277
		},
		{
			"name": "TOKENS",
			"amount": 231624645
		},
		{
			"name": "BEACONS",
			"amount": 57809
		},
		{
			"name": "EXP",
			"amount": 109056
		},
		{
			"name": "STARS",
			"amount": 999999842221
		},
		{
			"name": "SOULS",
			"amount": 0
		},
		{
			"name": "FRAGMENTS_STARS",
			"amount": 21862
		},
		{
			"name": "WHISHES_ROBOTS",
			"amount": 332
		},
		{
			"name": "WHISHES_PETS",
			"amount": 92
		},
		{
			"name": "FRAGMENTS_ASPECTS",
			"amount": 0
		},
		{
			"name": "FRAGMENTS_ARTEFACTS",
			"amount": 11
		},
		{
			"name": "DURABILITY",
			"amount": 0
		},
		{
			"name": "TIME",
			"amount": 2
		}
	],
	"stats": [
		{
			"name": "PLAYED_TIME",
			"displayName": "Temps de jeu",
			"color": "&b",
			"value": 843271718
		},
		{
			"name": "BLOCKS_MINED",
			"displayName": "Blocs minés",
			"color": "&e",
			"value": 4508337135
		},
		{
			"name": "BLOCKS_RAW_MINED",
			"displayName": "Blocs physique minés",
			"color": "&e",
			"value": 109056
		},
		{
			"name": "KILLS",
			"displayName": "Kills",
			"color": "&a",
			"value": 0
		},
		{
			"name": "DEATHS",
			"displayName": "Morts",
			"color": "&c",
			"value": 0
		},
		{
			"name": "TOKENS_EARNED",
			"displayName": "Tokens gagnés",
			"color": "&e",
			"value": 1001002401296426
		},
		{
			"name": "RINACOINS_EARNED",
			"displayName": "RinaCoins gagnés",
			"color": "&6",
			"value": 3020374915826911
		},
		{
			"name": "ITEMS_DROPPED",
			"displayName": "Objets trouvés",
			"color": "&e",
			"value": 672
		},
		{
			"name": "ITEMS_DESTROYED",
			"displayName": "Objets détruits",
			"color": "&c",
			"value": 458
		},
		{
			"name": "EXP_EARNED",
			"displayName": "EXP obtenus",
			"color": "&b",
			"value": 109056
		},
		{
			"name": "ROBOTS_CREATED",
			"displayName": "Robots fabriqués",
			"color": "&b",
			"value": 15
		},
		{
			"name": "ROBOTS_UPGRADED",
			"displayName": "Robots améliorés",
			"color": "&b",
			"value": 3
		},
		{
			"name": "PETS_INVOKED",
			"displayName": "Familiers invoqués",
			"color": "&d",
			"value": 250
		},
		{
			"name": "PETS_UPGRADED",
			"displayName": "Familiers évolués",
			"color": "&b",
			"value": 0
		}
	]
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
