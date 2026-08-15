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

# BedrockData-Legacy (Amber-PM) — MCPE 1.2.13 (protocol 223)

Original data blobs from the **PocketMine-MP** server for wire protocol **223** (Minecraft: Bedrock/Pocket Edition **1.2.13**), extracted from the real historical source code for that version — not reconstructed data or compatibility shims.

## Contents

```
resources/
├── creativeitems.json    # Creative inventory item list for the 1.2.13 client
├── recipes.json          # Crafting/furnace recipes recognized by the 1.2.13 client
└── runtimeid_table.json  # Block runtime-ID table expected by the 1.2.13 client
```

## Known issues

Protocol 223 support in AmberPM is **experimental**. See [`KNOWN_ISSUES.md`](KNOWN_ISSUES.md) for the current list of reproducible, unresolved problems affecting this legacy protocol (unreliable crafting results, recipe-book crashes, cross-version entity visibility issues).

## Origin

Extracted from `src/pocketmine/resources/` of the `PocketMine-MP-MultiProtocol` project (`master` branch), where `ProtocolInfo::CURRENT_PROTOCOL = 223` and `ProtocolInfo::MINECRAFT_VERSION = 'v1.2.13'`.

Sibling repo: [BedrockProtocol-Legacy](https://github.com/Amber-PM/BedrockProtocol-Legacy) · Full source: [Bedrock-MultiProtocol-Legacy](https://github.com/Amber-PM/Bedrock-MultiProtocol-Legacy)
