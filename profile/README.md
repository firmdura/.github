# Firmdura

**Embedded Linux security maintenance for device manufacturers.**

Firmdura is an independent engineering firm in Hamburg, Germany. We focus on the work between a known upstream security fix and a maintenance change that a manufacturer's engineers can review.

Our work covers CVE applicability assessment, patch adaptation, firmware builds, regression evidence, and EU Cyber Resilience Act reporting. Engagements are scoped to the product's existing source, configuration, hardware, and board support package.

We work with configurations based on Yocto, Buildroot, OpenWrt, and Debian/CIP. Builds and tests run in infrastructure the manufacturer controls or approves. Code review, signing keys, and deployment authority remain with the manufacturer.

## Open-source verification utilities

We publish the offline Go command-line tools and libraries used across our maintenance workflow under Apache-2.0 so customer teams can inspect how checks work, run them on air-gapped runners, and retain them without lock-in:

- **[cvedelta](https://github.com/firmdura/cvedelta)**: Compare versioned Yocto `cve-check` JSON reports with explicit scan provenance.
- **[triageguard](https://github.com/firmdura/triageguard)**: Recheck recorded local source, build-option, and patch-inventory assumptions behind prior CVE assessments.
- **[patchstack-audit](https://github.com/firmdura/patchstack-audit)**: Reproduce and audit ordered source patch stacks against SHA-256 manifests.
- **[firmwaredelta](https://github.com/firmdura/firmwaredelta)**: Review expected and unexpected file, permission, symlink, and ELF dependency changes between extracted firmware filesystems.
- **[bootlog-check](https://github.com/firmdura/bootlog-check)**: Check saved firmware boot logs against explicit milestones, timing deadlines, and forbidden patterns.

## Further information

- [Engineering workflow & open-source tooling](https://firmdura.com/how-it-works.html#tooling)
- [32-bit ARM backport walkthrough](https://firmdura.com/case-study.html)
- [Company information](https://firmdura.com/company.html)
- [Contact Firmdura](https://firmdura.com/contact.html)

---

Firmdura UG (haftungsbeschränkt) · Hamburg, Germany  
[firmdura.com](https://firmdura.com) · [info@firmdura.com](mailto:info@firmdura.com)
