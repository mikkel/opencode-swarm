Require Bun 1.4.4 or a patched Node branch (22.23.4, 24.22.1, or 26.12.1 and later) for the October 2026 runtime security fixes, including CVE-2026-111497 in Brotli response decoding. CI and release builds now select Bun 1.4.4 and Node 22.23.4.

Upgrade the actual Bun or Node runtime used by the OpenCode host, then restart that host. Updating this plugin alone does not replace an embedded host runtime. Plugin APIs and configuration are unchanged.
