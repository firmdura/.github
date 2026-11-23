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

## Reviewing a pilot handoff

1. Check the delivered files against the SHA-256 checksums in the [pilot handoff](https://firmdura.com/how-it-works.html#engagement). Pin the candidate layer or patch overlay to the supplied Git revision in your build.
2. For each CVE, read its status record (VEX) alongside the reference build and test results. If an agreed check failed or wasn't run, the case stays open.
3. Before signing your firmware, verify that the fix is in the image you built and test that image on your hardware. Passing reference tests do not establish that the fix is in your image.

## Public engineering work

Browse [Firmdura's public repositories](https://github.com/orgs/firmdura/repositories) for verification utilities and reference examples. Each example's test results apply to the build it describes.

---

Firmdura UG (haftungsbeschränkt) · Hamburg, Germany  
[firmdura.com](https://firmdura.com) · [info@firmdura.com](mailto:info@firmdura.com)
