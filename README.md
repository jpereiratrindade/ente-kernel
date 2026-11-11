# ENTE Kernel

A minimal experimental kernel for constitutive identity in modern C++.

The current implementation explores the smallest useful state capable of preserving identity through transformation.

## Properties

- immutable runtime identity;
- explicit transformation generation;
- explicit retirement;
- atomic mutable state;
- no heap allocation;
- no external dependencies;
- 16-byte kernel object, enforced at compile time.

## Files

```text
kernel.hpp
kernel.cpp
```

## Build

```bash
g++ -std=c++2c -Wall -Wextra -Wpedantic -c kernel.cpp
```

## Status

Experimental genesis.

The kernel is intentionally small. New state or abstractions should be added only when they prove constitutively necessary.

## License

GNU General Public License v3.0 (`GPL-3.0-only`). See [LICENSE](LICENSE).

## Premissas de desenvolvimento

**Simples, leve. Sempre pronto. Sempre incompleto!**

[Significado e símbolos das premissas](docs/sister-principles/README.md).
