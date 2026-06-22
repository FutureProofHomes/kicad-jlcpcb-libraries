# kicad-jlcpcb-libraries

Generated KiCad symbol libraries for JLCPCB/LCSC parts.

## Purpose

This repository contains published library artifacts generated automatically from the source repository.

- Source of truth: [FutureProofHomes/kicad-jlcpcb-library-generator](https://github.com/FutureProofHomes/kicad-jlcpcb-library-generator)
- Contents here are generated, not edited manually
- Updates are published by CI

## Usage
As a Git submodule
Add this repository to your project:
```bash
git submodule add https://github.com/FutureProofHomes/kicad-jlcpcb-libraries.git kicad-jlcpcb-libraries
git submodule update --init --recursive
```

## Contents

- `symbols/`: generated `.kicad_sym` files
- `manifest.json`: generation metadata
- `VERSION`: published version marker