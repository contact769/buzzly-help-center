# Formstack

Turn Formstack submissions into newsletter subscribers.

## Steps

1. In Buzzly, generate your webhook URL above and copy it.
2. In [Formstack](https://www.formstack.com), name your email field `email` (or `Email`), and your name fields `first_name`/`last_name` (any casing or spacing works, e.g. `First Name`).
3. Add the URL as a webhook/POST action in your form's settings.
4. Save, then submit a test entry.

## Troubleshooting

**The field-naming rule.** The field name itself must be in English, even if your form's visible labels are in another language — a field displayed as "Prénom" but named `first_name` still works; a field named "Prénom" does not.

**No name on subscribers.** Double-check your field names match `email`/`first_name`/`last_name` — translating the technical field name (not just the label) is the most common cause of missing names.

---

📖 **Read this page online:** [mybuzzly.com/en/docs/integrations/formstack](https://mybuzzly.com/en/docs/integrations/formstack)
