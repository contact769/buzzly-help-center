# Typeform

Turn Typeform responses into newsletter subscribers automatically.

## Steps

1. In Buzzly, generate your webhook URL above and copy it.
2. In your [Typeform form](https://www.typeform.com), open it from your Workspace, then select **Workflow** in the header.
3. In **Webhooks**, click **+**, paste the Buzzly URL into **Destination URL**, then save the webhook. Typeform requires an HTTPS URL.
4. Turn the new webhook **On**.
5. In Typeform, use **View deliveries → Send test request**, or submit a real test response, to confirm it arrives. See [Typeform's webhook guide](https://help.typeform.com/hc/en-us/articles/360029573471-Webhooks) if the labels differ in your account.
6. Buzzly reads the respondent's email answer automatically, and the first two text answers on your form whose field name contains "first" or "last" (e.g. `first_name`, `last_name`).

## Troubleshooting

**No name on new subscribers.** Make sure at least one of your text field names contains "first" or "last" — Buzzly can't guess otherwise.

**Nothing arrives.** Confirm the webhook is On in **Workflow → Webhooks**, inspect **View deliveries**, and submit a published response or Typeform test request (editor previews do not verify the live integration).

---

📖 **Read this page online:** [mybuzzly.com/en/docs/integrations/typeform](https://mybuzzly.com/en/docs/integrations/typeform)
