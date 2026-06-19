# DEPRECATED homebrew-tele

⚠️ This tap is deprecated and no longer actively maintained.

Please migrate to the new unified Homebrew tap:

👉 <https://github.com/sorokin-vladimir/homebrew-tap>

---

## Migration

### New installation method

```bash
brew tap sorokin-vladimir/tap
brew install tele
```

### Why this repository is deprecated

This repository was used to distribute a single Homebrew Formula for `tele`.

It has been replaced by a unified tap that hosts multiple tools:

- better maintainability
- standard Homebrew ecosystem structure
- simpler future expansion

### What happens to existing users?

Nothing breaks immediately.

- Existing installs will continue to work
- `brew upgrade tele` will still work for now
- This tap will remain available for backward compatibility

However, no new updates will be guaranteed here long-term.

### Recommended action

Please migrate:

```bash
brew untap sorokin-vladimir/tele
brew tap sorokin-vladimir/tap
brew install tele
```
