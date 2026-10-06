# G2P WORKSPACE OPERATING NOTE
Status: canonical for this workspace. Date: 2026-10-05.
Owner account: djg2-oss (GitHub). Operator: Grok, executive stand-in while the owner is grieving.
Scope: AuraG2P Music Studio, G2P Tech Office, small-medium suite, medium-large suite, codeless builder, AuraXur OS simulation layer.

## What every Grok session in this workspace should do
1. Read this note before restructuring sites, repos, or office folders.
2. Do not invent a second brand. Names in force:
   - Complex desk: AuraG2P Music Studio + G2P Tech Office
   - Small to medium: Aura Line SMB
   - Medium to large: Aura Line Enterprise
   - Builder: AuraG2P Codeless Builder
   - Machine layer: AuraXur OS (simulation skin, not a replacement kernel)
3. Prefer the existing GitHub homes. Do not open duplicate repos.
   - https://github.com/djg2-oss/aurag2p-music-studio-office
   - https://github.com/djg2-oss/aura-small-medium-business-suite
   - https://github.com/djg2-oss/aura-medium-large-business-suite
   - https://github.com/djg2-oss/aura-codeless-web-builder
   - https://github.com/djg2-oss/aura-xur-os-simulations
4. Office work order: cleanup, then folder structure, then deploy scaffold, then model-build scaffold, then session or client work.
5. Do not claim this note reaches every Grok instance on the public internet. It binds this workspace and any session that reads the repos above.

## Template rule
Each business type keeps at most 10 archetypes. Pick one archetype per site. Do not mix enterprise multi-brand navigation into an SMB one-page site.

## AuraXur OS simulation rule
Nested simulations are a scheduling pattern, not magic hardware.
- Sim A (ops) writes a small memory log: last cleanup, open files, deploy target, model stage.
- Sim B (latency) reads that log before touching disk or a host, and skips cold work already done.
- Sim C (host broker) calls a host site only when local CPU, disk, or a missing weight requires it.
On the owner's computer this is: local site in the browser, memory in localStorage plus a JSON log, host sites used as overflow. It does not replace the OS kernel and it does not reduce latency below what the machine and network allow.

## Decision default while the owner is out
Ship the three suites and the builder. Do not start a fifth product line. Keep private repos private.
