# Claude CAD releases

Signed releases of Claude CAD, a tool that lets Claude (in Claude Desktop) work in SolidWorks.

This repository holds **only the built downloads**. It is not the source code.

## Install

1. Download `ClaudeCad-vX.Y.Z.mcpb` from the [latest release](../../releases/latest).
2. Double-click it. Claude Desktop shows an install dialog.

## What is in a release

| File | What it is |
|---|---|
| `ClaudeCad-vX.Y.Z.mcpb` | The Claude Desktop extension (the app) |
| `skills-vN.zip` | Skills and design reference documents; applied automatically by the app |
| `manifest.json` | Names the files above with their SHA-256 hashes |
| `manifest.sig` | Signature over `manifest.json` |

The app only accepts a release whose manifest is signed with the key built into it, and checks every download against the hashes in that manifest.
