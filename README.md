# One Small Step

A bilingual, static website for people who say no to war, violence, and misogyny.

## Publishing with GitHub Pages

1. Upload the contents of this folder to a public GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.

## Approved steps

Submissions arrive privately in Tally and do not appear automatically. After review,
approved messages can be added to `steps.json` using this shape:

```json
{
  "steps": [
    {
      "id": "step-001",
      "language": "fa",
      "content": "متن قدم تأییدشده"
    }
  ]
}
```

Use `"fa"` for Persian and `"en"` for English. Do not publish names, contact details,
exact locations, or other identifying information.
