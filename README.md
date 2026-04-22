# Capsule Documentation

Documentation for [Capsule](https://github.com/beam-cloud/capsule), the Python framework for building agentic apps with chat, pages, collections, data handlers, tasks, schedules, integrations, and deployment tooling.

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

```text
├── docs.json              # Mintlify navigation and site config
├── index.mdx              # Landing page
├── installation.mdx       # SDK + CLI installation
├── quickstart.mdx         # Minimal Capsule app
├── tutorials/             # Step-by-step build guides
├── concepts/              # Mental model and architecture pages
├── reference/             # API and CLI reference
└── favicon.svg            # Site icon
```

## Contributing

1. Create a branch for your changes.
2. Run `mint dev` to preview locally.
3. Check for broken links and stale navigation entries in `docs.json`.
4. Submit a pull request.

## License

MIT License - see [LICENSE](LICENSE) for details.
