# Elementor

Turn Elementor form submissions into newsletter subscribers.

## Steps

1. In Buzzly, generate your webhook URL above and copy it.
2. In your [Elementor](https://elementor.com/help/actions-after-submit/) form widget, name your email field `email` and your name fields `first_name`/`last_name`.
3. Add the URL as a Webhook action under the form's "Actions After Submit".
4. Save, then submit a test entry.

## Troubleshooting

**The field-naming rule.** The field name itself must be in English, even if your form's visible labels are in another language.

**No name on subscribers.** Double-check your field names match `email`/`first_name`/`last_name` — translating the technical field name (not just the label) is the most common cause of missing names.

---

📖 **Read this page online:** [mybuzzly.com/en/docs/integrations/elementor](https://mybuzzly.com/en/docs/integrations/elementor)
