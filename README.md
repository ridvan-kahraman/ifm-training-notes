# IFM Training Notes (CR711S / CODESYS)

A lightweight, **example-driven** repository for IFM ecomatmobile / CR711S work.
Each example is a small, reproducible “mini-lab” with clear steps and expected results.

> ✅ Rule: Every example must be understandable **without extra docs**.
> ❌ No customer-specific / confidential data.

---

## Targets

- Devices: IFM CR711S
- Environment: CODESYS (V3.5 SP18 Patch 6)
- Scope: I/O, CAN, Diagnostics, Safety Patterns (Basic)

---

## Repository Structure

Each example lives in its own folder as shown below:

```
.gitattributes
.gitignore
.gitmessage
LICENSE
README.md
examples/
    index.md
    01_io/
        read-input-drive-output/
            README.md
            src/
        limit-switch-debounce/
            README.md
            src/
    02_can/
        receive-filter/
            README.md  
            src/
        decode-scaling/
            README.md
            src/
    ...

```