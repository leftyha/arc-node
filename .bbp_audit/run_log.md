# BBP Audit Run Log

## 2026-04-18 run-01
- Initialized `.bbp_audit/` state.
- Fingerprinted repository and captured hotspot file hashes.
- Mapped RPC attack surface for malachite-app.
- Confirmed unauthenticated admin mutation endpoints (`POST/DELETE /persistent-peers`).
- Recorded one confirmed finding, one strong hypothesis, and one ruled-out path traversal suspicion.
