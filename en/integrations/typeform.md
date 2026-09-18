# Typeform

Turn Typeform responses into newsletter subscribers automatically.

## Steps

1. In Buzzly, generate your webhook URL above and copy it.
2. In your [Typeform](https://www.typeform.com) form, open the Connect settings and add a Webhook.
3. Paste the URL and save.
4. Buzzly reads the respondent's email answer automatically, and the first two text answers on your form whose field name contains "first" or "last" (e.g. `first_name`, `last_name`).
5. Submit a test response to confirm it arrives.

## Troubleshooting

**No name on new subscribers.** Make sure at least one of your text field names contains "first" or "last" — Buzzly can't guess otherwise.

**Nothing arrives.** Confirm the webhook is still enabled in Typeform's Connect settings, and that you submitted a real response (previews don't fire webhooks).

---

📖 **Read this page online:** [mybuzzly.com/en/docs/integrations/typeform](https://mybuzzly.com/en/docs/integrations/typeform)
