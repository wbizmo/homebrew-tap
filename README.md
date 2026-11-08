# Toolip Homebrew Tap

Official planned Homebrew tap for [Toolip](https://github.com/wbizmo/toolip), maintained by **Zivora Labs**.

**Status: preparation only.** No formula or installable v3.2.1 release artifact has been published in this repository. Do not use a Homebrew install command until verified release assets and `Formula/toolip.rb` exist.

## Release plan

Implement the formula in [v3.2.1 Batch 17 / issue #112](https://github.com/wbizmo/toolip/issues/112), after validating standalone executables and their provenance. The formula must reference immutable, approved assets with exact version, architecture and SHA-256 digest. Test on supported macOS and Linux environments before publishing.

Once approved and published, the intended install command is:

```sh
brew install wbizmo/tap/toolip
```

**This command is not functional yet.** GitHub releases, npm publishing and tap formula activation remain subject to separate, explicit release approval.

## License

MIT License © 2026 **Zivora Logic Ventures**. Maintained by **Zivora Labs**. See [LICENSE](LICENSE).

This tap contains package installation metadata, not a fork of the Toolip security engine. Toolip source and release artifacts are maintained in [wbizmo/toolip](https://github.com/wbizmo/toolip).
