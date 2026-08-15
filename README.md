# BedrockData-Legacy (Amber-PM) — MCPE 1.2.13 (protocol 223)

Datos "blob" originales del servidor **PocketMine-MP** para el protocolo **223** (Minecraft: Bedrock/Pocket Edition **1.2.13**), extraídos del código fuente histórico real de esa versión — no son datos reconstruidos ni shims de compatibilidad.

## Contenido

```
resources/
├── creativeitems.json    # Lista de ítems del inventario creativo para el cliente 1.2.13
├── recipes.json          # Recetas de crafteo/horno reconocidas por el cliente 1.2.13
└── runtimeid_table.json  # Tabla de runtime IDs de bloques que espera el cliente 1.2.13
```

## Origen

Extraído de `src/pocketmine/resources/` del proyecto `PocketMine-MP-MultiProtocol` (rama `master`), donde `ProtocolInfo::CURRENT_PROTOCOL = 223` y `ProtocolInfo::MINECRAFT_VERSION = 'v1.2.13'`.

Repo hermano: [BedrockProtocol-Legacy](https://github.com/Amber-PM/BedrockProtocol-Legacy) · Fuente completa: [Bedrock-MultiProtocol-Legacy](https://github.com/Amber-PM/Bedrock-MultiProtocol-Legacy)
