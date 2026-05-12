# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

While the project is on `0.x`, MINOR-version bumps may break the public API
per SemVer §4.

## [0.2.0](https://github.com/fsafaei/concerto/compare/v0.1.1...v0.2.0) (2026-05-12)


### Features

* **benchmarks:** stage0_smoke env adapter for ego-AHT training (T4b.3) ([#74](https://github.com/fsafaei/concerto/issues/74)) ([c56df38](https://github.com/fsafaei/concerto/commit/c56df38ee2fefd59d31844ff55d3ff8d3e652378))
* **training,cli:** runtime device + chamber-spike train + GPU host kit (T4b.14 prep) ([#76](https://github.com/fsafaei/concerto/issues/76)) ([0a1b0ca](https://github.com/fsafaei/concerto/commit/0a1b0ca8952ad0e4784d3d888d18c8e5c096eee7))
* **training:** empirical-guarantee scaffolding + xfail trip-wire probe (T4b.13) ([#63](https://github.com/fsafaei/concerto/issues/63)) ([48f46e9](https://github.com/fsafaei/concerto/commit/48f46e92e5d2e0175281392773e13c7753060274))
* **training:** replace empirical-guarantee statistic with slope test (closes [#62](https://github.com/fsafaei/concerto/issues/62)) ([#72](https://github.com/fsafaei/concerto/issues/72)) ([75b5c7a](https://github.com/fsafaei/concerto/commit/75b5c7a69d84e127b0eb0da9cf39ae9f2b3e4a2f))


### Bug Fixes

* **training:** handle time-limit truncation in GAE bootstrap (issue [#62](https://github.com/fsafaei/concerto/issues/62) root cause) ([#70](https://github.com/fsafaei/concerto/issues/70)) ([e0819be](https://github.com/fsafaei/concerto/commit/e0819be91d0200d05243018fb2f7fcd3f07fae0b))


### Documentation

* **brand:** crop logo PNGs to their content bounding box ([#69](https://github.com/fsafaei/concerto/issues/69)) ([f42203b](https://github.com/fsafaei/concerto/commit/f42203beab6b9761b46b1d056e16552fd7546ec3))
* **brand:** use the white-text logo + size it to fit the docs header ([#68](https://github.com/fsafaei/concerto/issues/68)) ([2cde7d7](https://github.com/fsafaei/concerto/commit/2cde7d7bf690a3daf534a1a7aeb1032392d58505))
* **brand:** wire up the CONCERTO logo for README + mkdocs theme ([#67](https://github.com/fsafaei/concerto/issues/67)) ([0a1e2f7](https://github.com/fsafaei/concerto/commit/0a1e2f7ad06191870bfdbba0811ed26dfd147bd3))
* **readme:** add Zenodo DOI badge to the top of the badge row ([#61](https://github.com/fsafaei/concerto/issues/61)) ([718c14f](https://github.com/fsafaei/concerto/commit/718c14faf3fdb80a1858d94fce6a0b7a4bfc4c7a))
* **readme:** correct comparison table — purge Singh row, add precedent links ([#75](https://github.com/fsafaei/concerto/issues/75)) ([48a59e2](https://github.com/fsafaei/concerto/commit/48a59e2b19694e516466af79f201fbba479c78b9))
* **readme:** use ``/latest/`` versioned path for docs deep-links ([#65](https://github.com/fsafaei/concerto/issues/65)) ([1b6cf88](https://github.com/fsafaei/concerto/commit/1b6cf884a65cd6937540f56ac8f321b635957bb1))
* **readme:** wire up the Zenodo DOI in CITATION.cff and the bibtex ([#66](https://github.com/fsafaei/concerto/issues/66)) ([1c4a82c](https://github.com/fsafaei/concerto/commit/1c4a82c8200327c4630e9c591db2ff7f6d2513d8))

## [0.1.1](https://github.com/fsafaei/concerto/compare/v0.1.0...v0.1.1) (2026-05-11)


### Bug Fixes

* **release:** sync __version__ with pyproject + grant publish write perms ([#58](https://github.com/fsafaei/concerto/issues/58)) ([735d2db](https://github.com/fsafaei/concerto/commit/735d2db1cd1c08b3b02f9e398ccf4834ef25ee2e))

## [0.1.0](https://github.com/fsafaei/concerto/compare/v0.0.1...v0.1.0) (2026-05-11)


### Features

* **deps:** bump HARL fork to v0.1.0-aht (M4b-7) ([#38](https://github.com/fsafaei/concerto/issues/38)) ([489bbab](https://github.com/fsafaei/concerto/commit/489bbab26f2034de9dc09612532d89045ea3a9ec))
* **deps:** pin HARL fork at v0.0.0-vendored (T4b.2) ([#36](https://github.com/fsafaei/concerto/issues/36)) ([bf3847e](https://github.com/fsafaei/concerto/commit/bf3847e763b3fc8d7b06135d075c0436be8040b4))
* **partners:** add FrozenPartner Protocol + PartnerSpec dataclass (T4.1) ([#25](https://github.com/fsafaei/concerto/issues/25)) ([9e6541e](https://github.com/fsafaei/concerto/commit/9e6541e044e70cff23f67292b099313718a60e47))
* **partners:** add OpenVLA + CrossFormer Phase-1 stubs (T4.7) ([#28](https://github.com/fsafaei/concerto/issues/28)) ([6aa1d3a](https://github.com/fsafaei/concerto/commit/6aa1d3a5c60a2d347e7d8b9082fa4db9f1012ead))
* **partners:** add registry decorator + PartnerBase shield (T4.2 + T4.3) ([#26](https://github.com/fsafaei/concerto/issues/26)) ([02c5f31](https://github.com/fsafaei/concerto/commit/02c5f3114efa1651638a880d7f2653b155cf31ce))
* **partners:** add ScriptedHeuristicPartner + Phase-0 draft zoo (T4.4 + T4.8) ([#27](https://github.com/fsafaei/concerto/issues/27)) ([1639e90](https://github.com/fsafaei/concerto/commit/1639e90ea63c73fe81d15bf8885c2685ebeda330))
* **safety:** add hard braking fallback (T3.7) ([#17](https://github.com/fsafaei/concerto/issues/17)) ([c367cde](https://github.com/fsafaei/concerto/commit/c367cde0a2a85b00c1b97cc3243e0c28975ab22d))
* **safety:** add OSCBF two-level QP inner filter (T3.8) ([#18](https://github.com/fsafaei/concerto/issues/18)) ([a096da3](https://github.com/fsafaei/concerto/commit/a096da387cc677b36aa424d8ffbde9adc1a4711a))
* **safety:** add three-table safety report emitter (T3.9; ADR-014) ([#19](https://github.com/fsafaei/concerto/issues/19)) ([db13146](https://github.com/fsafaei/concerto/commit/db131463d3ff241b2ee137aea5b9d72942df9f7c))
* **safety:** replace M2 solve_qp_stub with real Clarabel benchmark (T3.10) ([#20](https://github.com/fsafaei/concerto/issues/20)) ([63bd6ec](https://github.com/fsafaei/concerto/commit/63bd6ec39f46a1ccacaa6b6936ae0311f8674a15))
* **scripts:** add HARL fork creation recipe + patches (T4b.1, T4b.4-T4b.7) ([#35](https://github.com/fsafaei/concerto/issues/35)) ([2528985](https://github.com/fsafaei/concerto/commit/25289858e0e63213cf68119c4dfea3967ba48347))
* **training:** add checkpoint save/load + SHA-256 integrity (T4b.12) ([#31](https://github.com/fsafaei/concerto/issues/31)) ([3a6e9a9](https://github.com/fsafaei/concerto/commit/3a6e9a963e1a7ac913e0650f108e01659cc3214b))
* **training:** add ego-AHT train() shell + chamber-side runner (T4b.11) ([#34](https://github.com/fsafaei/concerto/issues/34)) ([b9122a4](https://github.com/fsafaei/concerto/commit/b9122a457e25b128f963474091a891cd9b571e5a))
* **training:** add Hydra config scaffolding + EgoAHTConfig (plan/05 §2) ([#33](https://github.com/fsafaei/concerto/issues/33)) ([c0c3f92](https://github.com/fsafaei/concerto/commit/c0c3f92d8d65f343f97e1d2b50e0b379eabcca4e))
* **training:** add structured logging for ego-AHT runs (T4b.10) ([#30](https://github.com/fsafaei/concerto/issues/30)) ([046ba42](https://github.com/fsafaei/concerto/commit/046ba42989dbdc4a1310cd5b295c0f749d7b2606))
* **training:** EgoPPOTrainer + GAE property test (M4b-8a) ([#44](https://github.com/fsafaei/concerto/issues/44)) ([89c577b](https://github.com/fsafaei/concerto/commit/89c577b63ec63b3cb53e7458897ad6eae9c69ad8))


### Bug Fixes

* align axis count with ADR-007 revision 3 (four→six evaluation axes) ([#10](https://github.com/fsafaei/concerto/issues/10)) ([2c4b102](https://github.com/fsafaei/concerto/commit/2c4b1027f4ae9474decc05aaf33fd107f4a4bae7))
* **ci:** run OSV-Scanner via CLI to avoid SARIF/Code-Scanning gate ([#23](https://github.com/fsafaei/concerto/issues/23)) ([af2cca7](https://github.com/fsafaei/concerto/commit/af2cca734e44742cf0c7142a81dfb899e64f61b7))


### Documentation

* correct GitHub URLs and fix gh-pages root redirect ([#54](https://github.com/fsafaei/concerto/issues/54)) ([68a93cf](https://github.com/fsafaei/concerto/commit/68a93cf9eaec16aca571456538effd73999abee9))
* **partners:** add how-to/add-partner.md walkthrough + code-block test (T4.10) ([#29](https://github.com/fsafaei/concerto/issues/29)) ([76ca9bd](https://github.com/fsafaei/concerto/commit/76ca9bd6707c8d73e406736ddbd2015d12b18381))
* **readme:** rewrite README as researcher-first benchmark landing page ([#55](https://github.com/fsafaei/concerto/issues/55)) ([3ce9eea](https://github.com/fsafaei/concerto/commit/3ce9eea02c943efea7c8eb75ddd0c3f27665e39e))
* **safety:** expand why-conformal walkthrough + add code-block tests (T3.12) ([#22](https://github.com/fsafaei/concerto/issues/22)) ([1139f4e](https://github.com/fsafaei/concerto/commit/1139f4e3283d6f1ba64d17425e9722324bde81be))
* **tutorials:** replace hello-spike placeholder with M4b 1k-frame demo (T4b.15 partial) ([#37](https://github.com/fsafaei/concerto/issues/37)) ([ceefb1b](https://github.com/fsafaei/concerto/commit/ceefb1b594fef222b39df3776a9f8d7a5b81760a))

## [Unreleased]

### Added

- **M2 — Communication stack** (ADR-003, ADR-006).
  - `chamber.comm` public API: `CommChannel` Protocol, `CommPacket` /
    `Pose` / `TaskStatePredicate` TypedDicts, `SCHEMA_VERSION` constant,
    `ChamberCommError`, `ChamberCommQPSaturationWarning`.
  - `FixedFormatCommChannel` — schema-versioned encode/decode with a
    round-trip guarantee on the typed subset of state.
  - `AoIClock` — per-uid Age-of-Information accounting (Ballotta &
    Talak 2024 semantics).
  - `LearnedOverlay` — opt-in null-safe slot for jointly-trained B6
    partners (HetGPPO / CommFormer); Phase-1 fills in the encoder.
  - `CommDegradationWrapper` + `DegradationProfile` + the six named
    `URLLC_3GPP_R17` profiles (ideal / urllc / factory / wifi / lossy /
    saturation), anchored to URLLC + 3GPP Release 17 industrial-trial
    data. Per-step Bernoulli drop, clipped-Normal latency queue,
    AoI-aware delivery, telemetry counters via `CommDegradationStats`.
  - `saturation_guard` — fires `ChamberCommQPSaturationWarning` only
    under the `saturation` profile or when the QP solver exceeds the
    1 ms OSCBF target (ADR-004), pinning the contract for M3.
  - `concerto.training.seeding.derive_substream` — deterministic
    BLAKE2b-keyed seeding harness (P6) the comm channel and degradation
    wrapper draw from.
  - `concerto.safety.solve_qp_stub` — no-op QP placeholder so the
    saturation property test exists from M2 (M3 replaces it).
  - Stage-0 smoke (`chamber.benchmarks.stage0_smoke`) now composes
    `CommDegradationWrapper(FixedFormatCommChannel(), URLLC_3GPP_R17["factory"])`;
    the M1 stub channel is retired.
- **M1 — Platform stack** (ADR-001, ADR-005).
  - Three wrappers above ManiSkill v3 (`PerAgentActionRepeatWrapper`,
    `TextureFilterObsWrapper`, `CommShapingWrapper`) totalling under
    230 LOC, with `ChamberEnvCompatibilityError` for loud-fail under
    unsupported envs.
  - Stage-0 smoke env (`make_stage0_env`) reproducing the ADR-001
    3-robot acceptance scenario; CPU-only wrapper-structure tests cover
    conditions (a)/(b)/(c) and the Vulkan tier auto-skips when SAPIEN
    is unavailable.
- Repo scaffolding (M0): packaging, CI, docs, licence, hygiene scripts.
- Two top-level packages: `concerto` (METHOD) and `chamber` (BENCHMARK).

[Unreleased]: https://github.com/fsafaei/concerto/compare/v0.0.1.dev0...HEAD
