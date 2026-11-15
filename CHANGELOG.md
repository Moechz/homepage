# Changelog

All notable user-visible changes to the Homepage TOS application package.

## 2.8.0-1 — 2026-11-15

### Added
- First release. Homepage (`gethomepage/homepage:v2.8.0`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8147 and running
  as a non-root user (1000:1000).
- Persistent data is kept under `/Volume1/DockerAppData/homepagedocker/`.
