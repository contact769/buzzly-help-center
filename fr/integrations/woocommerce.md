# WooCommerce

Transformez vos commandes et clients WooCommerce en abonnés à votre newsletter.

## Étapes

1. Générez votre URL dans Buzzly et copiez-la.
2. Dans [WooCommerce](https://woocommerce.com/document/webhooks/) → Réglages → Avancé → Webhooks, ajoutez un webhook.
3. Réglez le sujet sur `Client créé` (ou `Commande créée`).
4. Collez l'URL comme URL de livraison, puis enregistrez.
5. Passez une commande test ou créez un client test.

## Dépannage

**Rien n'arrive.** Consultez le journal de livraison du webhook dans WooCommerce — une faute de frappe dans l'URL de livraison est la cause la plus fréquente, et WooCommerce y enregistre les tentatives échouées.

---

📖 **Lire cette page en ligne :** [mybuzzly.com/docs/integrations/woocommerce](https://mybuzzly.com/docs/integrations/woocommerce)
