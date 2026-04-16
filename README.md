# Public version channel

Plain-text version files for Oazys resources (`PerformHttpRequest` / `remoteVersionUrl`). Not the full source code.

## Layout

- `0azys-idcard/version` — channel for `0azys-idcard` (see `shared/resource_checker.lua` in that resource).
- `0azys-AdvancedVehicles/version` — channel for `0azys-AdvancedVehicles` (default raw URL in `shared/resource_checker.lua`).

Each file is a **single line** semver (e.g. `1.0.9`), no extra text.
