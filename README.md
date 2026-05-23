# Mintlify Starter Kit


<!-- mycelium-badges:start -->

<p>
  <a href="https://github.com/adelaidasofia/docs/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/adelaidasofia/docs?color=blue"></a>
  <a href="https://github.com/adelaidasofia/docs/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/adelaidasofia/docs?color=eab308"></a>
  <a href="https://github.com/adelaidasofia/docs/commits/main"><img alt="Last commit" src="https://img.shields.io/github/last-commit/adelaidasofia/docs"></a>
  <a href="https://github.com/adelaidasofia/docs/issues"><img alt="Open issues" src="https://img.shields.io/github/issues/adelaidasofia/docs"></a>
  <a href="https://myceliumai.co"><img alt="Built by Mycelium AI" src="https://img.shields.io/badge/built_by-Mycelium_AI-15B89A"></a>
</p>

<!-- mycelium-badges:end -->

Use the starter kit to get your docs deployed and ready to customize.

Click the green **Use this template** button at the top of this repo to copy the Mintlify starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## AI-assisted writing

Set up your AI coding tool to work with Mintlify:

```bash
npx skills add https://mintlify.com/docs
```

This command installs Mintlify's documentation skill for your configured AI tools like Claude Code, Cursor, Windsurf, and others. The skill includes component reference, writing standards, and workflow guidance.

See the [AI tools guides](/ai-tools) for tool-specific setup.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
