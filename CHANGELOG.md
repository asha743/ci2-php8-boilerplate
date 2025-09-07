# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.1.0] - 2025-09-07
### Added
- Initial release of **CodeIgniter 2 PHP 8 Boilerplate**.
- Declared dynamic properties across core classes (`Loader`, `Controller`, `Model`, `Input`, `URI`, `Router`) to remove PHP 8.2+ deprecation warnings.
- Updated database driver to use **mysqli** instead of removed `mysql_*` functions.

### Changed
- Patched `system/` core files to support **PHP 8.2/8.3**.
- Adjusted core constructors to modern `__construct()` style where necessary.
- Replaced legacy functions (`each()`, `create_function()`, etc.) with PHP 7+/8 equivalents.

### Notes
- This version serves as the **boilerplate foundation** for all future CI2-on-PHP8 projects.
- Focus is on **compatibility and stability**, not new framework features.

