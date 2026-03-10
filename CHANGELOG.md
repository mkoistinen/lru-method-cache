# Changelog

## 0.1.0

- Initial release.
- `lru_method_cache` decorator with per-instance LRU caching.
- Signature normalization for consistent cache keys.
- Automatic cleanup via `weakref.finalize`.
- Thread-safe with per-instance locks.
- `cache_info()` and `cache_clear()` support.
