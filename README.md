# Kiro Model

Workspace for the UAV flight simulator project.

## Contents

| Path | Description |
|------|-------------|
| `UAV/` | Fixed-wing UAV flight simulator (git submodule → `AkshayKumar2007-dev/UAV-SIH`) |

`UAV` is tracked as a git submodule because it is maintained as its own repository.
After cloning, initialize it with:

```bash
git clone --recurse-submodules https://github.com/AkshayKumar2007-dev/kiro-model.git
```

Or, if already cloned:

```bash
git submodule update --init --recursive
```

See `UAV/README.md` for build and run instructions for the simulator itself.
</｜｜DSML｜｜ parameter>