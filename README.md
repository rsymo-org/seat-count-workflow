# GitHub Action that notifies you when approaching seat limit
This action https://github.com/austenstone/seat-count-action, can be used to build a GitHub Actions workflow that notifies you about the remaining seats, e.g. send email to ABC (email/mailing list) when seat count is approaching 90%.
This gives prior warning and time to procure more seats to avoid situations like a new hires waiting for a seat.
Docs:
- Create a PAT: https://github.com/settings/tokens/new?scopes=admin:org
- If using Gmail for notifications:
    - About Gmail application password: https://support.google.com/mail/answer/185833
    - Create a Gmail application password: https://myaccount.google.com/apppasswords
- Setting the schedule: https://docs.github.com/en/enterprise-cloud@latest/actions/using-workflows/events-that-trigger-workflows#schedule




# seat-count-workflow

Original Action with instructions: https://github.com/austenstone/seat-count-action

The test implementation in this repo: https://github.com/rsymo-org/seat-count-workflow/blob/main/.github/workflows/main.yml

Setting the schedule: https://docs.github.com/en/enterprise-cloud@latest/actions/using-workflows/events-that-trigger-workflows#schedule
