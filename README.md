# SigmaOS Cinnamon desktop

This `no_std` crate models a desktop name, version, and selectable session
type. `initialize()` is currently a placeholder that returns success without
connecting to a display server, starting a window manager, or creating a
desktop session. Setting the session type changes only the in-memory value.

The inline tests exercise these model values and the placeholder return value;
they do not demonstrate a usable Cinnamon desktop or Wayland/X11 session.

## Build

```sh
cargo check --lib
```

## License

Apache-2.0. See [`Cargo.toml`](Cargo.toml).

## Inspiration

This component is inspired by Linux Mint and Omarchy Linux to provide:
- Single responsibility: One clear purpose
- Loose coupling: Minimal dependencies
- Stable interfaces: Well-defined APIs

## Status

- Architecture: Designed
- Implementation: Planned
- Testing: Planned
