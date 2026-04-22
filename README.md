# Airstore Documentation

Documentation for [Airstore](https://github.com/beam-cloud/airstore), the filesystem for AI agents.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Structure

```
├── index.mdx              # Introduction
├── quickstart.mdx         # Getting started guide
├── installation.mdx       # CLI installation
├── first-workflow.mdx     # Tutorial
├── concepts/              # Core concepts
├── sources/               # Source integrations
├── tools/                 # Tool usage
├── permissions/           # Access control
├── deployment/            # Deployment guides
├── reference/             # CLI and config reference
├── examples/              # Example workflows
└── troubleshooting/       # Common issues and FAQ
```

## Contributing

1. Fork the repository
2. Create a branch for your changes
3. Run `mint dev` to preview locally
4. Submit a pull request

## License

MIT License - see [LICENSE](LICENSE) for details.
