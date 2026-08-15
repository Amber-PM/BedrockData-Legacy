<p align="center">
	<a href="https://github.com/Amber-PM/Amber">
		<img src="https://raw.githubusercontent.com/Amber-PM/Amber/main/.github/readme/amberpm.png" width="128" height="128" alt="AmberPM Logo" title="AmberPM" />
	</a><br>
	<b>Part of AmberPM — a high-performance, multi-version fork of PocketMine-MP written in PHP</b>
</p>

<p align="center">
	<a href="https://github.com/Amber-PM/Amber"><img alt="AmberPM main repo" src="https://img.shields.io/badge/AmberPM-main%20repo-blue"></a>
	<a href="https://discord.gg/k55gScjTs3"><img src="https://img.shields.io/badge/Discord-Chat-5865F2?logo=discord&logoColor=white" alt="Discord" /></a>
	<a href="LICENSE"><img src="https://img.shields.io/badge/License-LGPL--3.0-blue.svg" alt="License" /></a>
</p>

# BedrockData (Amber-PM)

Data blobs used by **AmberPM** for its primary multi-version range: **v1.20.0 (protocol 589)** through **v1.26.30/40 (protocol ~1001-2168)**.

Sourced from `vendor/vapebw/bedrock-data` inside the AmberPM project.

## Contents

```
resources/vanilla/
```

Per-protocol data snapshots (block state maps, item ID maps, runtime-ID tables, biome definitions, creative items, recipes, etc.) covering every modern protocol version AmberPM supports concurrently.

## Note

This repo does **not** include data for legacy protocol 223 (MCPE 1.2.13) — that version predates the concepts these files describe (item type dictionary handshake, block-palette handshake, etc.) and is handled by a separate legacy compatibility layer instead. See [BedrockData-Legacy](https://github.com/Amber-PM/BedrockData-Legacy) and the `ADDING_LEGACY_VERSIONS.md` / `KNOWN_ISSUES.md` docs in the full Amber source repo for details.

## Origin

Extracted from `PockeT/vendor/vapebw/bedrock-data/` of the Amber-PM/Amber project.

## Origin

Extracted from `PockeT/vendor/vapebw/bedrock-data/` of the Amber-PM/Amber project.
