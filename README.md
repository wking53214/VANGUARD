# VANGUARD

Raw VANGUARD material, moved here from [DGK](https://github.com/wking53214/DGK)
once this repo existed — previously kept there deliberately as "raw
VANGUARD material, not something that needs its own destination" until
now.

## Contents

- **`vanguard-unified-governance-wrapper.py`**: `VanguardUnifiedGovernanceStack`
  ("VANGUARD-MASTER-HYBRID WRAPPER V10.0") — a perimeter-gate wrapper
  that runs a `PipelineCycleManager` forecast check before delegating to
  a `UnifiedSovereignKernel` ("DIT-GOV4-DGK Hybrid Kernel"). Both
  `PipelineCycleManager` and `UnifiedSovereignKernel` are defined in
  [GSA-GATEWAY](https://github.com/wking53214/GSA-GATEWAY)'s
  `governance-stack/` — this file doesn't define its own governance
  logic, it's VANGUARD's own branding wrapped around those two classes.
  Parses cleanly (real line breaks, no corruption).

- **`vanguard-behavioral-simulation-flattened.py`**: self-declared
  `SYSTEM NAME: VANGUARD (Validation Matrix & Neutral Governance
  Automated Routing Engine)` — "an advanced closed-loop behavioral
  simulation kernel designed to model, forecast..." per its own header.
  A single unbroken line (no real newlines at all — the filename says
  so), same flattening defect seen throughout this week's sweep. Kept
  as-is, not reconstructed; reconstructing real structure from a
  flattened file this size would mean guessing at intent.

The `SovereignGovernanceStack` files in GSA-GATEWAY's `governance-stack/`
also reference VANGUARD conceptually (as one of several subsystems it
wires together, alongside SRE, DIT, and a consensus engine) — those
stay in GSA-GATEWAY since they're multi-system integration code, not
VANGUARD-specific content.

## Runnable status

Neither file executes on its own. The wrapper parses but references
`PipelineCycleManager` / `UnifiedSovereignKernel` (supplied by GSA-GATEWAY)
and is a ~45-line sketch of the perimeter-gate pattern, not a working
integration. The behavioral-simulation file does not parse — it is a single
flattened line. This repository is a preserved architectural baseline, not
an executable system.

## License

Apache-2.0 — see `LICENSE` (matching the rest of this repo ecosystem).
