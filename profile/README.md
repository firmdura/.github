# Firmdura

**Shared security maintenance for embedded Linux.**

Auf Deutsch: [Sicherheitswartung für Embedded Linux](https://firmdura.com/de/security-maintenance.html) · [Ersteinschätzung anfragen](https://firmdura.com/de/contact.html)

Security fixes for the Linux base you already use, delivered as a versioned layer or patch overlay for your existing build system. The maintenance subscription covers agreed user-space components and includes build integration files and results from our reference tests.

Compatible products on the same supported base can use the same maintained patch release, including products from different manufacturers. Their applications and final firmware stay their own. During onboarding, we check relevant component revisions, configuration, and existing patches without requiring proprietary application source.

## Pilot scope and validation

To request a [free assessment](https://firmdura.com/contact.html), name your build system and include the release or branch if you know it. A line like “Yocto Kirkstone” is enough; you don't need to name a package or CVE.

If you have a suitable Yocto build, you can ask about a limited paid trial for one user-space CVE.

We quote the pilot separately. It covers three user-space CVEs with known upstream fixes on one pinned reference base. We agree the scope, fixed price, and acceptance criteria before work starts. Component coverage, response targets, release cadence, and support period are agreed before ongoing maintenance begins.

Firmdura owns reference validation. Your team owns final firmware builds, product and hardware tests, approval, signing, and deployment.

[Explore security maintenance](https://firmdura.com/security-maintenance.html) · [How it works](https://firmdura.com/how-it-works.html)

### Bases other than Yocto

These details help us assess whether we can support your release in a pilot:

- **Buildroot:** the Buildroot tag and `defconfig`.
- **OpenWrt:** the OpenWrt or vendor SDK release and feed revisions.
- **Debian/CIP:** the user-space snapshot and source package revisions.

## Public engineering work

These repositories contain verification utilities and reference examples that make individual engineering checks inspectable and reproducible. They support the maintenance work; the commercial product is the maintained patches and their release evidence. Each repository documents its own scope and limitations.

- [32-bit ARM Wget backport walkthrough](https://firmdura.com/case-study.html): completed component testing, with reproduction links and test boundaries.
- [Kirkstone reference sample](https://github.com/firmdura/meta-firmdura-kirkstone): source, reference-build evidence, and the sample's current status.

---

Firmdura UG (haftungsbeschränkt) · Hamburg, Germany  
[firmdura.com](https://firmdura.com) · [info@firmdura.com](mailto:info@firmdura.com)
