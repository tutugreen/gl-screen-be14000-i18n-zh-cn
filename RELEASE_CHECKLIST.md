# Release checklist

- Verify the device model, firmware version, and exact original screen package version.
- Update workflow compatibility metadata and scripts/repo_paths.py together.
- Validate language syntax, keys, references, and formatting placeholders.
- Require a passing build check before merging a PR.
- Test install, layout, upgrade, and removal on the matching device.
- Audit staged files for credentials, private notes, stock binaries, and build outputs.
- Dispatch the main workflow only after device testing.
- Check Release compatibility notes and IPK assets.
