# Capsule Documentation

Documentation for Capsule, the platform for building, deploying, and monetizing agentic apps with a few lines of Python.

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
├── index.mdx              # Docs landing page
├── installation.mdx       # Python + CLI setup
├── quickstart.mdx         # Fastest path to a live app
├── troubleshooting.mdx    # Common setup/runtime fixes
├── changelog.mdx          # User-facing updates
├── sdk-runtime-versions.mdx
├── build/                 # Step-by-step app-building guides
├── features/              # Feature pages
├── concepts/              # Deeper product and runtime models
├── reference/             # Python app API and CLI reference
├── style.css              # Mintlify style overrides
├── logo/                  # Logo assets
└── favicon.svg            # Site icon
```

## Contributing

1. Create a branch for your changes.
2. Run `mint dev` to preview locally.
3. Add every new public MDX page to `docs.json`.
4. Check for broken links and stale navigation entries.
5. Submit a pull request.

## License

MIT License - see [LICENSE](LICENSE) for details.
