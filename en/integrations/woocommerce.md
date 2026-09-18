# WooCommerce

Turn WooCommerce orders and customers into newsletter subscribers.

## Steps

1. In Buzzly, generate your webhook URL above and copy it.
2. In [WooCommerce](https://woocommerce.com/document/webhooks/) → Settings → Advanced → Webhooks, add a webhook.
3. Set the topic to `Customer created` (or `Order created`).
4. Paste the URL as the Delivery URL, then save.
5. Place a test order or create a test customer.

## Troubleshooting

**Nothing arrives.** Check the webhook's delivery logs in WooCommerce — a typo in the Delivery URL is the most common cause, and WooCommerce records failed delivery attempts there.

---

📖 **Read this page online:** [mybuzzly.com/en/docs/integrations/woocommerce](https://mybuzzly.com/en/docs/integrations/woocommerce)
