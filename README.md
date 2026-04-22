# Capsule Documentation

Documentation for [Capsule](https://github.com/beam-cloud/capsule), the platform for building, deploying, and monetizing agentic apps with a few lines of Python.

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
├── installation.mdx       # Python + CLI setup
├── quickstart.mdx         # Fastest path to a live app
├── tutorials/             # Step-by-step build guides
├── concepts/              # Platform model and capability pages
├── reference/             # Python app API and CLI reference
└── favicon.svg            # Site icon
```

## Contributing

1. Create a branch for your changes.
2. Run `mint dev` to preview locally.
3. Check for broken links and stale navigation entries in `docs.json`.
4. Submit a pull request.

## License

MIT License - see [LICENSE](LICENSE) for details.
