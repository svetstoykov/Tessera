# Tessera

An independent C# functional port of Keycloak, with OpenIddict providing the OAuth 2.0/OpenID Connect foundation and idiomatic .NET extensibility.

The goal is a complete, self-hosted identity and access management product: deploy it as supplied, configure it for most requirements, and extend it in C# for the rest. Planned NuGet packages will help .NET applications sign users in, protect APIs, and call protected APIs.

**Current state:** planning scaffold only. No identity server, NuGet packages, compatibility guarantees, or production-ready implementation exists yet.

This project is independent of Keycloak and Duende and is not endorsed by either. Keycloak is the upstream product being ported, and provenance will be preserved for translated or adapted material. The intended project license is [Apache 2.0](LICENSE); third-party material retains its applicable terms.

Local product planning and agent rules live under the gitignored `docs/` directory. Agent entry points are [AGENTS.md](AGENTS.md) and [CLAUDE.md](CLAUDE.md).
