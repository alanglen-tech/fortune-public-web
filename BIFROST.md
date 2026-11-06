# BIFROST — Repository governance instructions (2026-11-06)

**Application:** `fortune-public-web`
**Canonical control point:** `C:\Users\alanj\JARVIS_LAB\00_CONTROL\bifrost_gateway.py` on the authorised Mission Control PC.
**Specific constraints:** Public website: do not mutate deployed marketing content without verified preview and deployment gate.

For each material code or workflow change, begin with actual source SHA, current environment, identity, existing tests, and measurable outcome. Follow these seven independent gates in order: **FIND → BUILD → TEST → BREAK → REPAIR → RETEST → VERIFY**. Each gate records a mission ID, current source revision, task owner, acceptance criteria, test/negative evidence, Independent Affairs result, next owner, next destination and verified rollback. Gate status is **YES, NO or UNKNOWN**; neither a developer declaration nor a successful build alone counts as evidence.

Before any gate advances, use the local BIFROST gateway to register the mission and submit an evidence packet in its safe inbox. The gateway independently checks permitted evidence and rejects missing/mismatched checks, unsupported claims, wrong stage and self-approved assertions. Record the exact gateway receipt and source SHA in the change summary. An **UNKNOWN** result is a hold, not a success. Independent Affairs must challenge negative cases and failures, repair and retest before release. A discovery opportunity goes separately to Crazy Scientist and may not block routine work or change production.

**Safety:** preserve source, rollback, permissions, secrets and live integrations. Do not confuse local synthetic protocol tests with functional product tests, staging with production, or documentation with working runtime enforcement. No charges or external publication without specific authorization. Application-specific acceptance and CI still apply.

**Activation truth (2026-11-06):** These governance instructions are now on the default branch. They do not, by themselves, connect the application's runtime to Mission Control, enforce mandatory GitHub checks, or deploy an autonomous scheduler. The local BIFROST gateway is active on Mission Control; per-application build/release hooks and real-product acceptance still require verification before universal compliance can be claimed.
