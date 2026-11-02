# Source SBOM

**Initial source snapshot, not a release report.** Source commit `074f4ab7732a9e37c1dc07d10bf3048e294bce0b` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/libfap `074f4ab7732a9e37c1dc07d10bf3048e294bce0b`

- sbom:role: source-root
- sbom:git-commit: 074f4ab7732a9e37c1dc07d10bf3048e294bce0b
- sbom:git-tree: 6eb513aed66b75d816bbe5e67aa7e26438d0ca01
- sbom:source-repository: https://github.com/wave-owl/libfap
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "COPYING", "sha256": "efc0525431cb97e2ba274772c8f204f85b88b18f1dcce26c54553506a0b4728c"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/libfap | 074f4ab7732a9e37c1dc07d10bf3048e294bce0b | source-root | unresolved; manual review required |
| Conditional source requirements declared by configure.ac | unresolved | conditional-build-runtime-requirement | unresolved |
| Autotools C library; configure.ac/src/Makefile.am define compilation | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
