# Typeform

Transformez les réponses à vos formulaires Typeform en abonnés à votre newsletter.

## Étapes

1. Dans Buzzly, générez votre URL de webhook ci-dessus et copiez-la.
2. Dans votre formulaire [Typeform](https://www.typeform.com), ouvrez-le depuis votre espace de travail, puis sélectionnez **Workflow** dans l'en-tête.
3. Dans **Webhooks**, cliquez sur **+**, collez l'URL Buzzly dans **Destination URL**, puis enregistrez le webhook. Typeform exige une URL HTTPS.
4. **Activez-le**.
5. Dans Typeform, utilisez **View deliveries → Send test request**, ou envoyez une vraie réponse test, pour confirmer sa réception. Consultez le [guide des webhooks Typeform](https://help.typeform.com/hc/en-us/articles/360029573471-Webhooks) si les libellés de votre compte diffèrent.
6. Buzzly lit automatiquement la réponse email du répondant, ainsi que les deux premières réponses texte dont le nom du champ contient « first » ou « last » (ex. `first_name`, `last_name`).

## Dépannage

**Pas de nom sur les nouveaux abonnés.** Vérifiez qu'au moins un de vos champs texte contient « first » ou « last » dans son nom — Buzzly ne peut pas deviner autrement.

**Rien n'arrive.** Vérifiez que le webhook est actif dans **Workflow → Webhooks**, consultez **View deliveries**, puis envoyez une réponse publiée ou une requête de test Typeform (les aperçus de l'éditeur ne vérifient pas l'intégration en direct).

---

📖 **Lire cette page en ligne :** [mybuzzly.com/docs/integrations/typeform](https://mybuzzly.com/docs/integrations/typeform)
