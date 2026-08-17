# Summa Legal

Static support and privacy pages for **Summa: Money Tracker**.

## Pages

- `/support/`
- `/privacy-policy/`

## Local preview

No dependencies or build step are required. From this directory, run:

```sh
python3 -m http.server 8080
```

Then open:

- `http://localhost:8080/support/`
- `http://localhost:8080/privacy-policy/`

## Deployment

The site is compatible with static hosting, including GitHub Pages.

For GitHub Pages:

1. Push this directory to a repository named `summa-legal`.
2. In the repository settings, open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `master` branch and the `/ (root)` folder.

For the GitHub account `vlraio`, the resulting URLs are expected to be:

- `https://vlraio.github.io/summa-legal/support/`
- `https://vlraio.github.io/summa-legal/privacy-policy/`

If a custom domain is configured, use the equivalent `/support/` and
`/privacy-policy/` URLs on that domain.
