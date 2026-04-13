# Contributing to Fire's Extension Pack

Thanks for your interest in contributing!

## Adding or Removing Extensions

1. Fork and clone the repository.
2. Edit `package.json` — add or remove entries in the `extensionPack` array.
   - Use the format `publisher.extension-name`.
3. Bump the `version` field in `package.json`.
4. Submit a pull request describing why the extension should be added or removed.

## Guidelines

- Each extension should be useful for general development workflows (C++, GDScript, remote dev, formatting, etc.).
- Avoid extensions that duplicate functionality already covered by the pack.
- Keep the extension list alphabetically ordered where practical.

## Publishing

The extension is published automatically via the GitHub Actions workflow in `.github/workflows/publish.yaml` when a new tag is pushed.

## License

By contributing, you agree that your contributions will be licensed under the same license as this project.
