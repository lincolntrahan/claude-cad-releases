# Claude CAD releases

Releases of Claude CAD, a tool that lets Claude (in Claude Desktop) work in SolidWorks.

This repository holds **only the built downloads**. It is not the source code.

## Install

1. Download `ClaudeCad-vX.Y.Z.mcpb` from the [latest release](../../releases/latest).
2. In Claude Desktop open **Settings > Extensions**, then either drag the file into the Extensions panel or use **Advanced settings > Install Extension** and choose it. Confirm the install, and restart Claude Desktop if it asks.

## What is in a release

| File | What it is |
|---|---|
| `ClaudeCad-vX.Y.Z.mcpb` | The Claude Desktop extension (the app) |
| `skills-vN.zip` | Skills and design reference documents; applied automatically by the app |
| `manifest.json` | Names the files above with their SHA-256 hashes |

The app fetches `manifest.json` over HTTPS, checks each download against the hash in it, and keeps any skill you have edited.
Releases are published by the repository owner's GitHub account.
