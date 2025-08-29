# ⚠️ This Repository Has Been Archived

This monorepo has been split into two separate, more focused repositories:

## 🚀 New Repositories

### [langfuse-client-base](https://github.com/genai-rs/langfuse-client-base)
[![Crates.io](https://img.shields.io/crates/v/langfuse-client-base.svg)](https://crates.io/crates/langfuse-client-base)
[![Documentation](https://docs.rs/langfuse-client-base/badge.svg)](https://docs.rs/langfuse-client-base)

Auto-generated OpenAPI client for the Langfuse API. This package provides the low-level, type-safe bindings.

```toml
[dependencies]
langfuse-client-base = "0.1"
```

### [langfuse-ergonomic](https://github.com/genai-rs/langfuse-ergonomic)
[![Crates.io](https://img.shields.io/crates/v/langfuse-ergonomic.svg)](https://crates.io/crates/langfuse-ergonomic)
[![Documentation](https://docs.rs/langfuse-ergonomic/badge.svg)](https://docs.rs/langfuse-ergonomic)

Ergonomic wrapper with builder patterns for the Langfuse API. This package provides a user-friendly interface.

```toml
[dependencies]
langfuse-ergonomic = "0.1"
```

## Migration Guide

If you were using this repository, update your dependencies:

**Old (monorepo):**
```toml
langfuse-rs = { git = "https://github.com/timvw/langfuse-rs" }
```

**New (separate packages):**
```toml
# For direct API access:
langfuse-client-base = "0.1"

# For ergonomic builder patterns:
langfuse-ergonomic = "0.1"
```

## Why the Split?

- **Clear separation of concerns**: Generated code vs handwritten ergonomic layer
- **Independent versioning**: Each package can evolve at its own pace
- **Simpler maintenance**: Generated code has minimal CI/CD requirements
- **Better discoverability**: Each package has a focused purpose

## Status

This repository is archived and will no longer receive updates. Please use the new repositories for:
- 🐛 Bug reports
- ✨ Feature requests
- 🤝 Contributions

---

*This repository was archived on 2025-08-29 in favor of the new modular architecture under the [genai-rs](https://github.com/genai-rs) organization.*