# Formstack

Transformez les soumissions de vos formulaires Formstack en abonnés à votre newsletter.

## Étapes

1. Générez votre URL dans Buzzly et copiez-la.
2. Dans [Formstack](https://www.formstack.com), nommez votre champ email `email` (ou `Email`), et vos champs de nom `first_name`/`last_name` (la casse et les espaces n'ont pas d'importance, par ex. `First Name`).
3. Ajoutez l'URL comme action webhook/POST dans les paramètres de votre formulaire.
4. Enregistrez, puis envoyez une entrée test.

## Dépannage

**La règle du nom de champ.** Le nom technique du champ doit rester en anglais, même si les libellés visibles de votre formulaire sont en français — un champ affiché comme « Prénom » mais nommé `first_name` fonctionne ; un champ nommé « Prénom » ne fonctionne pas.

**Pas de nom sur les abonnés.** Vérifiez que vos noms de champs correspondent bien à `email`/`first_name`/`last_name` — traduire le nom technique du champ (et pas seulement son libellé) est la cause la plus fréquente des noms manquants.

---

📖 **Lire cette page en ligne :** [mybuzzly.com/docs/integrations/formstack](https://mybuzzly.com/docs/integrations/formstack)
