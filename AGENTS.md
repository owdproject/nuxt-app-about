# About app

This repository owns the Nuxt About app. Read the [Nuxt extension contract](https://github.com/owdproject/nuxt/blob/main/docs/extension-contract.md) before changing its integration. The app owns its window content and presentation; host templates decide whether to include it.

Preserve user changes. Use `@owdproject/nuxt` authoring APIs and never depend on the deprecated unscoped `nuxt-desktop` package. Verify integrations in a standalone playground with local packs and Verdaccio; do not publish to public npm during local verification.
