# OSS Docker Scanner

This GitHub Actions project scans a Docker image or ZIP file for OSS license compliance using:
- Syft
- Tern
- SCANOSS
- Docker Scout (optional)
- Excel output builder

## Usage
Trigger the workflow manually via GitHub Actions and provide:
- Docker image reference (`ghcr.io/...`) or
- ZIP URL pointing to a saved Docker image (`*.tar`) or source code

Results will include JSON outputs from each tool and an Excel summary.

