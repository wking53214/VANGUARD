# VANGUARD

**Retired 2026-09-03.** Two preserved files. Canonical home for this content: a separate private repository. Not on the live path.

## 1. Pipeline Position & Role

**ARCHIVED PERIMETER SKETCH.** Explicitly excluded from the live pipeline. Moved out of another private repository because it had nowhere else to go.

## 2. Full System Scope & Architectural Depth

- `vanguard-behavioral-simulation-flattened.py` — minified pipeline: contradictory term pairs, regime classifier (`STABLE|UNSTABLE|CRITICAL` at 0.35/0.65), HMAC-SHA256 default key **`"default-vanguard-key"`**, actuation clip magic numbers. Docstring claims ESN/Lyapunov; **code has neither**.
- `vanguard-unified-governance-wrapper.py` — 45 lines referencing **undefined** `PipelineCycleManager`, `UnifiedSovereignKernel`, `system_logger`. Hardcoded secret `"Coldfire"`. `asyncio.run` → `NameError`.

IOError on log write is swallowed (`pass`) — **fail-open on audit**.

## 3. What It Does NOT Do / Non-Goals

Forecast, Lyapunov stability, wrap a real kernel, govern actuation.

## 4. Brutally Honest Current Status & Gaps

Already retired. Archiving the GitHub repo is bookkeeping. Flattened file `__main__` demo may run; wrapper does not. Default HMAC key is public.

## 5. Core Invariants & Guarantees

None you should rely on. Wrapper *would* `REJECTED / VANGUARD_ANOMALY` if it imported.

## 6. Inputs, Outputs & Type Contracts

`SystemInputStructure(text_content_body, numeric_metric_value, metadata_map)` in the flattened file.

## 7. Stack Integration Topology

None. This repository is retired and not on the live path.

Apache-2.0.
