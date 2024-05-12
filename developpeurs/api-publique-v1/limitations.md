# ⚠️ Limitations

{% hint style="warning" %}
Les clés API ont par défaut une limite de **60 requêtes par minute**.
{% endhint %}

Vous retrouverez les informations de la limitation dans le header de la requête de réponse :&#x20;

* `RateLimit-Limit` - Indiquant la limite de votre clé API.&#x20;
* `RateLimit-Remaining` - Indiquant le nombre de requêtes restantes dans la minute.&#x20;
* `RateLimit-Reset` - Indiquant le temps restant en secondes avant le reset de la limitation.&#x20;

{% hint style="info" %}
Si vous avez besoin d'augmenter la limite de votre clé API, veuillez contacter adrien2431#2431 par MP Discord en expliquant la raison précise.
{% endhint %}
