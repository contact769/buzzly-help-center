# Typeform

Transformez les réponses à vos formulaires Typeform en abonnés à votre newsletter.

## Étapes

1. Dans Buzzly, générez votre URL de webhook ci-dessus et copiez-la.
2. Dans votre formulaire [Typeform](https://www.typeform.com), ouvrez les paramètres Connect et ajoutez un Webhook.
3. Collez l'URL et enregistrez.
4. Buzzly lit automatiquement la réponse email du répondant, ainsi que les deux premières réponses texte dont le nom du champ contient « first » ou « last » (ex. `first_name`, `last_name`).
5. Envoyez une réponse test pour confirmer qu'elle arrive.

## Dépannage

**Pas de nom sur les nouveaux abonnés.** Vérifiez qu'au moins un de vos champs texte contient « first » ou « last » dans son nom — Buzzly ne peut pas deviner autrement.

**Rien n'arrive.** Vérifiez que le webhook est toujours actif dans les paramètres Connect de Typeform, et que vous avez soumis une vraie réponse (les aperçus ne déclenchent pas les webhooks).

---

📖 **Lire cette page en ligne :** [mybuzzly.com/docs/integrations/typeform](https://mybuzzly.com/docs/integrations/typeform)
